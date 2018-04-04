cmake_minimum_required(VERSION 2.8)
project( HelloOpenCV )

find_package(OpenCV REQUIRED)
add_executable( HelloOpenCV HelloOpenCV.cpp )
target_link_libraries( HelloOpenCV ${OpenCV_LIBS} )