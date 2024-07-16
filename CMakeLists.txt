cmake_minimum_required(VERSION 2.8)
project(TEST)

set(CMAKE_XX_FLAGS "${CMAKE_CXX_FLAGS} -Wall")

set(CMAKE_BUILD_TYPE Debug)

include_directories(${CMAKE_SOURCE_DIR}/include)

add_executable(my_cmake_exe main.cpp src/test.cpp)