cmake_minimum_required(VERSION 3.0)
project(jasonutils)
include_directories(include/main)
add_library(jasonutils SHARED src/main/add.cpp src/main/subtract.cpp)

install(TARGETS jasonutils LIBRARY DESTINATION lib)
install(FILES include/main/jasonutils.h DESTINATION include)