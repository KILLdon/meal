cmake_minimum_required(VERSION 3.13)
include(../utils.cmake)
project(assert C)

set(CMAKE_C_STANDARD 11)

create_meal_library(INTERFACE log)