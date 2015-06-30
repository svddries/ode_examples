cmake_minimum_required(VERSION 2.8.3)
project(ode_example)

set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -std=c++11")

add_executable(ode_example src/ode_example.cpp)
target_link_libraries(ode_example ode)
