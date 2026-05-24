cmake_minimum_required(VERSION 3.5)

add_library(formatter STATIC
    sources/formatter.cpp
)

target_include_directories(formatter PUBLIC include)
