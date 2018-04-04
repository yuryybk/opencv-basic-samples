cmake_minimum_required(VERSION 2.8)
project( DisplayImage )

find_package(OpenCV REQUIRED)
add_executable( PyrUpPyrDown PyrUpPyrDown.cpp )
target_link_libraries( PyrUpPyrDown ${OpenCV_LIBS} )