cmake_minimum_required(VERSION 3.28.3)
project(fastnoiselite)


add_library(fastnoiselitelib INTERFACE)
target_include_directories(fastnoiselitelib INTERFACE C)
