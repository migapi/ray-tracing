cmake_minimum_required(VERSION 2.8 FATAL_ERROR)
add_definitions(-std=c++11)

cmake_minimum_required(VERSION 2.8 FATAL_ERROR)
SET(sampleName ray-tracer)

add_executable (ray-tracer color.h main.cc vec3.h)