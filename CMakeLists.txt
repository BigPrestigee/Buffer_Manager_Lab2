cmake_minimum_required(VERSION 3.23)
project(Buffer_Manager_Lab2)

set(CMAKE_CXX_STANDARD 14)

include_directories(.)

add_executable(Buffer_Manager_Lab2
        BMgr.cpp
        BMgr.h
        DSMgr.cpp
        DSMgr.h
        main.cpp
        )
