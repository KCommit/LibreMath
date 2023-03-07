cmake_minimum_required(VERSION 3.20)
project(LibreMath)


set(CMAKE_CXX_STANDARD 11)

include_directories(${PROJECT_SOURCE_DIR}/include)
add_subdirectory(lib)
add_subdirectory(test)
