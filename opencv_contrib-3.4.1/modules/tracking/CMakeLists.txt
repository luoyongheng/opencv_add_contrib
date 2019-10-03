set(the_description "Tracking API")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -std=c++11")
ocv_define_module(tracking opencv_imgproc opencv_core opencv_video opencv_plot OPTIONAL opencv_dnn opencv_datasets WRAP java python)
ocv_warnings_disable(CMAKE_CXX_FLAGS -Wno-shadow /wd4458)
