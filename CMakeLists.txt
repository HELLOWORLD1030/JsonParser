cmake_minimum_required(VERSION 3.21)
project(cJSON C)

set(CMAKE_C_STANDARD 99)

add_executable(cJSON main.c json.h json.c)
