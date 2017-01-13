project(ARLib)

cmake_minimum_required(VERSION 2.8)

aux_source_directory(./src DIR_SRCS)

add_executable(ARLib ${DIR_SRCS})

set(CMAKE_BUILD_TYPE Debug)