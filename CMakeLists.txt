cmake_minimum_required(VERSION 3.16)
project(tcp_ip)

set(CMAKE_CXX_STANDARD 20)

add_executable(tcp_ip main.cpp graph/graph.cpp graph/graph.hpp)