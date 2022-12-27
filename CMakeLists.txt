cmake_minimum_required(VERSION 3.10)

# set the project name
project(solid-design)

# specify the c++ standard
set (CMAKE_CXX_STANDARD 14)
set (CMAKE_CXX_STANDARD_REQUIRED True)

# add the executable
add_executable(solid-design
	src/main.cpp
	)
