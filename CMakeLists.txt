cmake_minimum_required(VERSION 3.5)

project(tinyrenderer)

file(GLOB SOURCES *.h *.cpp)

add_executable(${PROJECT_NAME} ${SOURCES})