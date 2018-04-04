cmake_minimum_required(VERSION 2.8)
project( BorderBox )

find_package(OpenCV REQUIRED)
add_executable( BorderBox BorderBox.cpp )
target_link_libraries( BorderBox ${OpenCV_LIBS} )