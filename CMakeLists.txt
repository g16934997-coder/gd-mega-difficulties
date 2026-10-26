cmake_minimum_required(VERSION 3.25)

project(MegaDifficultiesMod)

find_package(Geode REQUIRED)

add_geode_mod(
    g16934997.mega_difficulties
    VERSION 1.0.0
    CONTAINS_GEODE_FILES
)

target_sources(${GEODE_MOD_ID} PRIVATE src/main.cpp)
