cmake_minimum_required(VERSION 4.1)
project(PirateGame)

set(CMAKE_CXX_STANDARD 20)
find_package(SDL2 REQUIRED)
add_executable(PirateGame main.cpp)
target_link_libraries(PirateGame PRIVATE SDL2::SDL2)