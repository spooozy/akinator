cmake_minimum_required(VERSION 3.24)
project(akinator C)

set(CMAKE_C_STANDARD 11)

add_executable(akinator akinator/main.c akinator/Header.h akinator/Source.c)


