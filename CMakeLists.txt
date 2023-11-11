cmake_minimum_required(VERSION 3.23)
project(CS301_Assignment81)

set(CMAKE_CXX_STANDARD 14)

include_directories(.)

add_executable(CS301_Assignment81
        Heap.h
        HeapSort.h
        PQ.in
        PQ.out
        PQ.Secreen
        PQDr.cpp
        PQType.h
        README.md
        ReadMe.txt)
