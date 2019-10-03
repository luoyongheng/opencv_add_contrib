set(the_description "Biologically inspired algorithms")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -std=c++11")
ocv_warnings_disable(CMAKE_CXX_FLAGS -Wundef)
ocv_define_module(bioinspired opencv_core OPTIONAL opencv_highgui opencv_ocl WRAP java python)
