set(the_description "Fuzzy mathematical image processing")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -std=c++11")
ocv_define_module(fuzzy opencv_imgproc opencv_core WRAP python)
