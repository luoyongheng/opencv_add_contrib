set(the_description "Optical Flow Algorithms")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -std=c++11")
ocv_define_module(optflow opencv_core opencv_imgproc opencv_video opencv_ximgproc opencv_imgcodecs WRAP python)
