cmake_minimum_required(VERSION 3.15)

add_library(ComputerRoom INTERFACE)
target_include_directories(ComputerRoom
    INTERFACE
    ${CMAKE_CURRENT_SOURCE_DIR})