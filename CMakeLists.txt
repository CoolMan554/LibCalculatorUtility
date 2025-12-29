cmake_minimum_required(VERSION 3.10)

project(static_math_library)

add_library(math STATIC
        library_math.cpp
)

target_include_directories(math
        PUBLIC
        ${CMAKE_CURRENT_SOURCE_DIR}
)