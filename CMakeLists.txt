cmake_minimum_required(VERSION 3.25)

set(CMAKE_CXX_STANDARD 23)
set(CMAKE_CXX_STANDARD_REQUIRED ON)
project(learnGDB VERSION "")

add_executable(learnGDB main.cpp)
target_include_directories(learnGDB PRIVATE .)