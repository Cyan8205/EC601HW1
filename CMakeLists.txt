cmake_minimum_required(VERSION 2.8)
project( SmileDetect )
find_package( OpenCV REQUIRED )
add_executable( SmileDetect smiledetect.cpp )
target_link_libraries( SmileDetect ${OpenCV_LIBS} )


