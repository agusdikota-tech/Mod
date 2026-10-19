cmake_minimum_required(VERSION 3.21)
project(InputBufferMod CXX)

find_package(Geode REQUIRED)

geode_target_pin(input_buffer_mod)

add_geode_mod(input_buffer_mod
    src/main.cpp
)