cmake_minimum_required(VERSION 3.5)

add_library(formatter_ex STATIC
    sources/formatter_ex.cpp
)

target_include_directories(formatter_ex PUBLIC include)

target_link_libraries(formatter_ex formatter)
