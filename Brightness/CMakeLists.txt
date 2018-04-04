cmake_minimum_required(VERSION 2.8)
project( Brightness )

find_package(OpenCV REQUIRED)
add_executable( Brightness Brightness.cpp )
target_link_libraries( Brightness ${OpenCV_LIBS} )