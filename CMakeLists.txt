cmake_minimum_required(VERSION 3.17)
project(Multiple_Files C)

set(CMAKE_C_STANDARD 99)

add_executable(Multiple_Files main.c Test.c Test.h main.h)