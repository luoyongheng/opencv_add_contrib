set(the_description "Object Detection")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -std=c++11")
#uncomment the following line to enable parallel computing
#add_definitions(-DHAVE_TBB)

ocv_define_module(dpm opencv_core opencv_imgproc opencv_objdetect OPTIONAL opencv_highgui WRAP python)

ocv_warnings_disable(CMAKE_CXX_FLAGS /wd4512) # disable warning on Win64
