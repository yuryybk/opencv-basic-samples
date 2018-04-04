cmake_minimum_required(VERSION 2.8)
project( WrapAffine )

find_package(OpenCV REQUIRED)
add_executable( WrapAffine WrapAffine.cpp )
target_link_libraries( WrapAffine ${OpenCV_LIBS} )