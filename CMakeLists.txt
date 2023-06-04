cmake_minimum_required(VERSION 3.0.0 FATAL_ERROR)
project(Detours C CXX)

add_library(detours src/detours.cpp src/modules.cpp src/image.cpp src/creatwth.cpp src/disasm.cpp src/disolarm.cpp src/disolarm64.cpp src/disolia64.cpp src/disolx64.cpp src/disolx86.cpp)
target_include_directories(detours PUBLIC include)
