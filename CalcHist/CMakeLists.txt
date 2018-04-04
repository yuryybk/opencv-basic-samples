cmake_minimum_required(VERSION 2.8)
project( CalcHist )

find_package(OpenCV REQUIRED)
add_executable( CalcHist CalcHist.cpp )
target_link_libraries( CalcHist ${OpenCV_LIBS} )