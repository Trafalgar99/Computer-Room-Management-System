cmake_minimum_required(VERSION 3.15)

add_library(teacher teacher.cpp)

target_include_directories(teacher PUBLIC ${CMAKE_CURRENT_SOURCE_DIR})

target_link_libraries(teacher PUBLIC Identity orderFile)