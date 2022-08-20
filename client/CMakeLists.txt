cmake_minimum_required(VERSION 3.20.0)
project(client VERSION 0.1.0)

SET(CMAKE_RUNTIME_OUTPUT_DIRECTORY ${PROJECT_BINARY_DIR}/../bin)

file(GLOB project
    src/*
)
add_executable(${PROJECT_NAME} ${project})


