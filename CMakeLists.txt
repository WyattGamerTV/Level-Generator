cmake_minimum_required(VERSION 3.25)

if(NOT DEFINED GEODE_SDK)
    set(GEODE_SDK "${CMAKE_CURRENT_SOURCE_DIR}/geode-sdk")
endif()

project(LevelGenerator)

include("${GEODE_SDK}/cmake/Geode.cmake")

add_geode_mod(
    LevelGenerator
    wyattgamertv.level_generator
    src/main.cpp
)
