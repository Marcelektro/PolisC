cmake_minimum_required(VERSION 3.24)
project(PolisC)

set(CMAKE_CXX_STANDARD 17)
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -static")

add_executable(PolisC main.cpp iostream.h)
