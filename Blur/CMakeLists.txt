cmake_minimum_required(VERSION 2.8)
project( Blur )

find_package(OpenCV REQUIRED)
add_executable( Blur Blur.cpp )
target_link_libraries( Blur ${OpenCV_LIBS} )