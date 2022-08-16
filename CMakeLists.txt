cmake_minimum_required(VERSION 3.16.3)
project(Breakout VERSION 1.0)

set(CMAKE_CXX_STANDARD 17)

set(SOURCES main.cpp )

add_executable(${PROJECT_NAME} ${SOURCES})
target_include_directories(${PROJECT_NAME} PRIVATE ./inc)