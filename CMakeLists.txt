cmake_minimum_required(VERSION 3.12)

project("top-k-elementos" VERSION 1.0.0)

add_executable(app "src/main.cpp" "src/hash.cpp" "src/heap.cpp")