cmake_minimum_required(VERSION 2.8)
project( Threshold )

find_package(OpenCV REQUIRED)
add_executable( Threshold Threshold.cpp )
target_link_libraries( Threshold ${OpenCV_LIBS} )