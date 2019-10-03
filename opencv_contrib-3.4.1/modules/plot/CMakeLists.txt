set(the_description "Plot function for Mat data.")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -std=c++11")
ocv_define_module(plot opencv_core opencv_imgproc WRAP python java)
