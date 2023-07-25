cmake_minimum_required(VERSION 3.15)
add_library(manager  manager.cpp)

target_include_directories(manager PUBLIC ${CMAKE_CURRENT_SOURCE_DIR})

target_link_libraries(manager PUBLIC Identity student teacher ComputerRoom)