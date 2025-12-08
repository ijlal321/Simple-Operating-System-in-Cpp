cmake_minimum_required(VERSION 3.20)
project(Hellow LANGUAGES CXX)

add_library(MyLib STATIC my_lib.cpp)
add_executable(Hellow main.cpp)

target_link_libraries(Hellow PUBLIC MyLib)
