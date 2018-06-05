cmake_minimum_required(VERSION 3.9)
project(simplen)

set(CMAKE_CXX_STANDARD 11)
set(CMAKE_CXX_FLAGS -lcurl)

add_executable(simplen src/main.cpp)
target_link_libraries(simplen curl)