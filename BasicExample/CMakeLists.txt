cmake_minimum_required(VERSION 3.26.0)

project(OurGame)

add_executable(${PROJECT_NAME} main.cpp)

target_link_libraries(${PROJECT_NAME} ${CMAKE_SOURCE_DIR}/libYAVE.a)