cmake_minimum_required(VERSION 3.14.5)

set(CMAKE_CXX_STANDARD 11)
set(BUILD_SHARED_LIBS ON)

project(tbb_link_example)

add_subdirectory(project1)
add_subdirectory(tests)
