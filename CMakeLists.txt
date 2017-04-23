cmake_minimum_required(VERSION 2.8)
project(test1)
set(PROJECT test1)

SET(EXECUTABLE_OUTPUT_PATH ${PROJECT_SOURCE_DIR}/bin)
message(STATUS ${EXECUTABLE_OUTPUT_PATH})

set(SOURCE_FILES main.cpp)
add_executable(test1 ${SOURCE_FILES})
