cmake_minimum_required(VERSION 3.13)
project(Tp2)

set(CMAKE_CXX_STANDARD 14)
set(CMAKE_AUTOMOC ON)

find_package(Qt5Widgets CONFIG REQUIRED)

add_executable(Tp2 main.cpp)

target_link_libraries(Tp2 Qt5::Widgets)