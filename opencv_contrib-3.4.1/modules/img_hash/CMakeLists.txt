set(the_description "Image hash algorithms")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -std=c++11")
set(OPENCV_MODULE_IS_PART_OF_WORLD OFF)
ocv_define_module(img_hash opencv_imgproc opencv_core WRAP python java)
