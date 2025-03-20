cmake_minimum_required(VERSION 3.15)

set(PROJECT_NAME test)
project("${PROJECT_NAME}")

set(CMAKE_CXX_STANDARD 17)
set(CMAKE_CXX_EXTENSIONS OFF)
set(CMAKE_CXX_STANDARD_REQUIRED TRUE)

set(CXX_FLAGS "-O1")

include_directories("inc/")

add_executable("${PROJECT_NAME}" main.cpp)