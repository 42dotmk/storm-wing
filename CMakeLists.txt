# storm-wing root CMake
cmake_minimum_required(VERSION 3.23)

project(storm-wing
  VERSION 0.0.1
  LANGUAGES CXX
)

set(CMAKE_CXX_STANDARD 23)
set(CMAKE_CXX_STANDARD_REQUIRED ON)

add_subdirectory(src)
