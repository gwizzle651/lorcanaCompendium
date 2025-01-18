cmake_minimum_required(VERSION 3.5)
project(lorcanaCompendium
        VERSION 0.0.1
        DESCRIPTION "A tool for keeping track of your Lorcana trading cards."
        LANGUAGES CXX)
add_executable(lorcanaCompendiumBinary main.cpp)
target_compile_features(lorcanaCompendiumBinary PRIVATE cxx_std_20)
