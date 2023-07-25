cmake_minimum_required(VERSION 3.15)

add_subdirectory(teacher)
add_subdirectory(ComputerRoom)
add_subdirectory(Identity)
add_subdirectory(manager)
add_subdirectory(student)
add_subdirectory(orderFile)

add_executable(main main.cpp)

target_link_libraries(main
    PUBLIC
    ComputerRoom
    Identity
    manager
    orderFile
    student
    teacher
)

# include_directories(${CMAKE_SOURCE_DIR}/Include)
