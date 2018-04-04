cmake_minimum_required(VERSION 2.8)
project( MorphologyTransformations )

find_package(OpenCV REQUIRED)
add_executable( MorphologyTransformations MorphologyTransformations.cpp )
target_link_libraries( MorphologyTransformations ${OpenCV_LIBS} )