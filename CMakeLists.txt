cmake_minimum_required(VERSION 3.25)

project(LevelGenerator)

include($ENV{GEODE_SDK}/cmake/Geode.cmake)

add_geode_mod(
    LevelGenerator
    wyattgamertv.level_generator
    src/main.cpp
)
