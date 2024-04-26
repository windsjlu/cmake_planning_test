cmake_minimum_required(VERSION 3.10)
project(my_planning_first)

set(CMAKE_CXX_STANDARD 11)

include_directories(${PROJECT_SOURCE_DIR}/include)
aux_source_directory(. SRC_LISTS)

set(EXECUTABLE_OUTPUT_PATH ${PROJECT_SOURCE_DIR}/bin)
add_executable(my_planning_first ${SRC_LISTS})