cmake_minimum_required(VERSION 3.15.2)
project(jasonutils)
include_directories(include/main)
add_library(jasonutils SHARED src/main/add.c)

install(TARGETS jasonutils)