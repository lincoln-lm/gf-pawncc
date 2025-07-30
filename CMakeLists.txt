#build file for CMake, see http://www.cmake.org/

CMAKE_MINIMUM_REQUIRED(VERSION 3.10)
PROJECT(gf-pawncc)

add_definitions(-DPAWN_CELL_SIZE=64)
add_definitions(-DNDEBUG)

ADD_SUBDIRECTORY(./compiler)
