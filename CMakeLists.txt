cmake_minimum_required(VERSION 3.24)
project(template_project)

set(CMAKE_BUILD_TYPE Debug)

set(CMAKE_CXX_STANDARD 20)
set(CMAKE_CXX_STANDARD_REQUIRED TRUE)

# Set the library name and source files
file(GLOB_RECURSE SRC_FILES "src/*.cpp")


# Create the shared library
add_executable("1.out" ${SRC_FILES})
