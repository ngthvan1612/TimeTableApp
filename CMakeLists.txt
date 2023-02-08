cmake_minimum_required(VERSION 3.24)
project(TimeTableApp)

set(CMAKE_CXX_STANDARD 17)

add_executable(TimeTableApp main.cpp TimeTableItem.cpp TimeTableItem.h)
