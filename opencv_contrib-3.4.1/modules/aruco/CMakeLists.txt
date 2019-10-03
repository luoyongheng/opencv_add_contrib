set(the_description "ArUco Marker Detection")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -std=c++11")
ocv_define_module(aruco opencv_core opencv_imgproc opencv_calib3d WRAP python java)
