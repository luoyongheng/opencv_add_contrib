set(the_description "Line descriptor")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -std=c++11")
ocv_define_module(line_descriptor opencv_imgproc OPTIONAL opencv_features2d WRAP python)
