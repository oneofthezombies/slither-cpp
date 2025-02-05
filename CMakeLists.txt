cmake_minimum_required(VERSION 3.20)
project(slither_cpp)

add_executable(slither_cpp_server src/slither_cpp/server/main.cc)
target_include_directories(slither_cpp_server PRIVATE src)
