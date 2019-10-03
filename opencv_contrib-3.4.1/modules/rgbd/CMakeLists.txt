set(the_description "RGBD algorithms")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -std=c++11")
ocv_define_module(rgbd opencv_core opencv_calib3d opencv_imgproc WRAP python)
