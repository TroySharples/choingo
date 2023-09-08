cmake_minimum_required(VERSION 3.18)

set(PROJECT_NAME "choingo")
project(${PROJECT_NAME} VERSION 1.0 LANGUAGES CXX)

add_compile_options(-Wall -Wextra -Wpedantic -Wno-missing-field-initializers)

add_subdirectory(apps)
add_subdirectory(src)
