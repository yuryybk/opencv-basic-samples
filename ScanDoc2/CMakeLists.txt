cmake_minimum_required(VERSION 2.8)
project( ScanDoc2 )

find_package(OpenCV REQUIRED)
add_executable( ScanDoc2 ScanDoc2.cpp )
target_link_libraries( ScanDoc2 ${OpenCV_LIBS} )