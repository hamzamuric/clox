cmake_minimum_required(VERSION 3.17)
project(clox C)

set(CMAKE_C_STANDARD 11)

add_executable(clox main.c common.h chunk.h chunk.c memory.h memory.c debug.c debug.h value.c value.h)