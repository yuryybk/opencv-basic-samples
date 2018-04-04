cmake_minimum_required(VERSION 2.8)
project( ImageMoments )

find_package(OpenCV REQUIRED)
add_executable( ImageMoments ImageMoments.cpp )
target_link_libraries( ImageMoments ${OpenCV_LIBS} )