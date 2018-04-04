cmake_minimum_required(VERSION 2.8)
project( ScanDoc1 )

find_package(OpenCV REQUIRED)
add_executable( ScanDoc1 ScanDoc1.cpp )
target_link_libraries( ScanDoc1 ${OpenCV_LIBS} )