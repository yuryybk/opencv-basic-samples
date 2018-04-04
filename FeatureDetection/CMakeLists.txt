cmake_minimum_required(VERSION 2.8)
project( FeatureDetector )

find_package(OpenCV REQUIRED)
add_executable( FeatureDetector FeatureDetector.cpp )
target_link_libraries( FeatureDetector ${OpenCV_LIBS} )