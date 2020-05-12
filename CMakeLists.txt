cmake_minimum_required(VERSION 3.15)
project(bitfield-enum-class LANGUAGES CXX)
add_library(${PROJECT_NAME})
target_include_directories(
    ${PROJECT_NAME} INTERFACE ${CMAKE_CURRENT_SOURCE_DIR}/include)
