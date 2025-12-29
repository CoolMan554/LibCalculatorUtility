cmake_minimum_required(VERSION 3.5)

project(static_math_library)

add_library(libMath STATIC
        library_math.cpp
)

target_include_directories(libMath
        PUBLIC
        ${CMAKE_CURRENT_SOURCE_DIR}
)