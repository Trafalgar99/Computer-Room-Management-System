cmake_minimum_required(VERSION 3.15)

add_library(orderFile orderFile.cpp)

target_include_directories(orderFile PUBLIC
    ${CMAKE_CURRENT_SOURCE_DIR}

    # ${CMAKE_SOURCE_DIR}/Include
)
