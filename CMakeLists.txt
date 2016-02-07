cmake_minimum_required(VERSION 3.3)
project(AES)

set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wall -Werror")


set(SOURCE_FILES main.c main.c)
add_executable(AES ${SOURCE_FILES})