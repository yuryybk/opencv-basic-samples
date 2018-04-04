cmake_minimum_required(VERSION 2.8)
project( DilateErode )

find_package(OpenCV REQUIRED)
add_executable( DilateErode DilateErode.cpp )
target_link_libraries( DilateErode ${OpenCV_LIBS} )