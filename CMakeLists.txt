cmake_minimum_required(VERSION 3.19)
project(realtime_project1 C)

set(CMAKE_C_STANDARD 11)

add_executable(realtime_project1 main.c customer.c shelving_team.c)
