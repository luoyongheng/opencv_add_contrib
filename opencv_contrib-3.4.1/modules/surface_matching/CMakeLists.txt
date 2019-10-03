set(the_description "3D point features")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -std=c++11")
ocv_define_module(surface_matching opencv_core opencv_flann WRAP python)
