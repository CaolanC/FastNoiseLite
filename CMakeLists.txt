cmake_minimum_required(VERSION 3.2)
project(fastnoiselite)

add_library(fastnoiselitelib INTERFACE)
target_include_directories(fastnoiselitelib INTERFACE C)
