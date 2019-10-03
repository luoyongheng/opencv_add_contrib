set(the_description "Image Registration")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -std=c++11")
ocv_define_module(reg opencv_imgproc opencv_core WRAP python)
