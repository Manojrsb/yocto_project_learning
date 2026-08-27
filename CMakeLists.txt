cmake_minimum_required(VERSION 3.10)
project(hello-world)

add_executable(hello hello.cpp)

install(TARGETS hello DESTINATION bin)
