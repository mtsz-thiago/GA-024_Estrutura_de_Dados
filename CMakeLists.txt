cmake_minimum_required(VERSION 3.22)

project(EstruturaDeDados)

#version number
set (EstruturaDeDados_VERSION_MAJOR 0)
set (EstruturaDeDados_VERSION_MINOR 1)

add_executable (hello_world.exe hello_world.c)

# Indicate which libraries to include during the link process.
# target_link_libraries (CMakeHelloWorld Hello)

install (TARGETS hello_world.exe DESTINATION bin)