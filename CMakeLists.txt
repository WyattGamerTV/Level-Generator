cmake_minimum_required(VERSION 3.25)
project(LevelGenerator)

find_package(Geode REQUIRED)

add_geode_mod(
    LevelGenerator
    wyattgamertv.level_generator
    src/main.cpp
)
