cmake_minimum_required(VERSION 2.8)
project( ApplyKernel )

find_package(OpenCV REQUIRED)
add_executable( ApplyKernel ApplyKernel.cpp )
target_link_libraries( ApplyKernel ${OpenCV_LIBS} )