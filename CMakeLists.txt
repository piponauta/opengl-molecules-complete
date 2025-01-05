cmake_minimum_required(VERSION 3.12)

option(BUILD_LIBSOIL_STATIC "Build libSOIL as a static lib" ON)

project(opengl-molecules VERSION 1.0.0)

add_subdirectory(libSOIL)
add_subdirectory(opengl-molecules)
