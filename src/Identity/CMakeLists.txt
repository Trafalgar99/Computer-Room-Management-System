cmake_minimum_required(VERSION 3.15)

add_library(Identity INTERFACE)
target_include_directories(Identity INTERFACE ${CMAKE_CURRENT_SOURCE_DIR})