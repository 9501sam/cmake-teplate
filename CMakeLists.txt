cmake_minimum_required(VERSION 3.12)
project(cmake-example)

add_executable(MyExecutable src/main.c src/helper.c)

target_include_directories(MyExecutable PRIVATE include)
