cmake_minimum_required(VERSION 4.1)
project(fluid_project)

set(CMAKE_CXX_STANDARD 20)

include_directories(.)

add_executable(fluid_project main.cpp lbfgs.c)
