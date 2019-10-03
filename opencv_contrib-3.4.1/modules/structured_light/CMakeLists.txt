set(the_description "Structured Light API")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -std=c++11")
ocv_define_module(structured_light opencv_core opencv_imgproc opencv_calib3d opencv_phase_unwrapping OPTIONAL opencv_viz WRAP python java)
