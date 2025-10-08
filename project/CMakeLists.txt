cmake_minimum_required(VERSION 3.15)
project(hello LANGUAGES CXX)

set(CMAKE_CXX_STANDARD 11)
set(EXECUTABLE_OUTPUT_PATH ${CMAKE_CURRENT_SOURCE_DIR}/bin)

add_executable(hello ${CMAKE_CURRENT_SOURCE_DIR}/hello.cpp)

# message(${CMAKE_CURRENT_SOURCE_DIR})