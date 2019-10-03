set(the_description "Object Detection using CNNs")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -std=c++11")
ocv_define_module(dnn_objdetect opencv_core opencv_imgproc opencv_dnn
    OPTIONAL opencv_highgui opencv_imgcodecs  # samples
)
