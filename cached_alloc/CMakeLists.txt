cmake_minimum_required(VERSION 3.13)
include(../utils.cmake)
project(cached_alloc C)

set(CMAKE_C_STANDARD 11)

create_meal_library(PUBLIC alloc PRIVATE basket assert macros math memory)