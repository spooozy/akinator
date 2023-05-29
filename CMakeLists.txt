cmake_minimum_required(VERSION 3.24)
project(akinator C)

set(CMAKE_C_STANDARD 11)

add_executable(akinator akinator/akinator.c akinator/Header.h akinator/Source.c)


