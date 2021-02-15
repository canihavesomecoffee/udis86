cmake_minimum_required(VERSION 3.12)
project(udis86 LANGUAGES C)

include_directories("${PROJECT_SOURCE_DIR}")

add_subdirectory(libudis86)
add_subdirectory(udcli)
