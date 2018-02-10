cmake_minimum_required(VERSION 3.8)
project(sqlite_amalgamation_3220000)

set(CMAKE_CXX_STANDARD 11)

set(SOURCE_FILES
        shell.c
        sqlite3.c
        sqlite3.h
        sqlite3ext.h
        mian.cpp
        mian.h)

add_executable(sqlite_amalgamation_3220000 ${SOURCE_FILES})