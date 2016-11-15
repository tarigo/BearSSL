cmake_minimum_required(VERSION 3.6)
project(BearSSL)

set(BearSSL_VERSION_MAJOR 0)
set(BearSSL_VERSION_MINOR 1)

set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS}")

include_directories(inc)

add_subdirectory(src)
add_subdirectory(samples)

