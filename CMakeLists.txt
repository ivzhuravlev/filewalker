cmake_minimum_required(VERSION 3.20)

project(filewalker LANGUAGES CXX)

add_executable(filewalker
 src/main.cpp
)

target_compile_features(filewalker PRIVATE cxx_std_20)
