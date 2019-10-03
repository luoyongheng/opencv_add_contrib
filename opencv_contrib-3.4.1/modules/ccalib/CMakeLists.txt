set(the_description "Custom Calibration Pattern")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -std=c++11")
ocv_define_module(ccalib opencv_core opencv_imgproc opencv_calib3d opencv_features2d opencv_highgui WRAP python)
