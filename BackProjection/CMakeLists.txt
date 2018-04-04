cmake_minimum_required(VERSION 2.8)
project( BackProjection )

find_package(OpenCV REQUIRED)
add_executable( BackProjection BackProjection.cpp )
target_link_libraries( BackProjection ${OpenCV_LIBS} )