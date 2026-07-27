cmake_minimum_required(VERSION 3.10)

project(Hello)

set(CMAKE_CXX_STANDARD 14)

add_library(library library.cpp library.h)

add_executable(Hello main.cpp)

target_link_libraries(Hello library)