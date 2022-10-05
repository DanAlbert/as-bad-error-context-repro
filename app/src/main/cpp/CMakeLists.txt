cmake_minimum_required(VERSION 3.22.1)
project("Android Studio Bad Error Context Repro" VERSION 1.0.0 LANGUAGES C CXX)

add_library(app SHARED app.cpp)
