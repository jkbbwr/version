cmake_minimum_required(VERSION 3.12)

project(version)

include_directories(include)

add_library(version STATIC src/lib.c)
