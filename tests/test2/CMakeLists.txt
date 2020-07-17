cmake_minimum_required(VERSION 3.15)

project(test2 LANGUAGES CXX)

add_executable(test2 main.cpp)
target_link_libraries(test2 gtest)
add_test(NAME test2 COMMAND test2)
