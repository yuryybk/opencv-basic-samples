cmake_minimum_required(VERSION 2.8)
project( CornerDetection )

find_package(OpenCV REQUIRED)
add_executable( CornerDetection CornerDetection.cpp )
target_link_libraries( CornerDetection ${OpenCV_LIBS} )