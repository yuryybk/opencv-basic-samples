cmake_minimum_required(VERSION 2.8)
project( CompareHist )

find_package(OpenCV REQUIRED)
add_executable( CompareHist CompareHist.cpp )
target_link_libraries( CompareHist ${OpenCV_LIBS} )