cmake_minimum_required(VERSION 3.10)
project(problem_043)

set(CMAKE_CXX_STANDARD 17)
set(CMAKE_CXX_STANDARD_REQUIRED ON)

add_executable(code main.cpp)

# Set output name to "code" as required by OJ
set_target_properties(code PROPERTIES OUTPUT_NAME "code")