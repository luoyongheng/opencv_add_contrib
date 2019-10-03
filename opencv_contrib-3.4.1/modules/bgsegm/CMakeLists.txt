set(the_description "Background Segmentation Algorithms")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -std=c++11")
ocv_define_module(bgsegm opencv_core opencv_imgproc opencv_video opencv_calib3d WRAP python java)
