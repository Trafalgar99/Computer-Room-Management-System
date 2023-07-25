cmake_minimum_required(VERSION 3.15)

project(ComputerRoomManagementSystem)

add_subdirectory(src)
add_subdirectory(Include)

include_directories(${PROJECT_SOURCE_DIR}/Include)