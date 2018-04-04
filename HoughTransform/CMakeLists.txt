cmake_minimum_required(VERSION 2.8)
project( HoughTransform )

find_package(OpenCV REQUIRED)
add_executable( HoughTransform HoughTransform.cpp )
target_link_libraries( HoughTransform ${OpenCV_LIBS} )