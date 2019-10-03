set(the_description "Stereo Correspondence")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -std=c++11")
ocv_define_module(stereo opencv_imgproc opencv_features2d opencv_core opencv_calib3d)
