cmake_minimum_required(VERSION 3.16)

project(hello_qt)

set(CMAKE_CXX_STANDARD 17)

find_package(Qt6 REQUIRED COMPONENTS Widgets)

add_executable(hello_qt main.cpp)

target_link_libraries(hello_qt Qt6::Widgets)


