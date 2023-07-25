cmake_minimum_required(VERSION 3.15)

add_library(student student.cpp)

target_include_directories(student PUBLIC ${CMAKE_CURRENT_SOURCE_DIR})

target_link_libraries(student PUBLIC Identity orderFile ComputerRoom)