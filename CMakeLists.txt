cmake_minimum_required(VERSION 3.10)
project(mahjong C CXX)

set(CMAKE_C_STANDARD 99)

add_subdirectory(src)
add_subdirectory(mahjong_evaluator)
add_subdirectory(tst)
