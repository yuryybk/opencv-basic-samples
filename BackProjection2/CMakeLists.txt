cmake_minimum_required(VERSION 2.8)
project( BackProjection2 )

find_package(OpenCV REQUIRED)
add_executable( BackProjection2 BackProjection2.cpp )
target_link_libraries( BackProjection2 ${OpenCV_LIBS} )