cmake_minimum_required(VERSION 3.0)
project(EmberBrowser)

set(CMAKE_CXX_STANDARD 20)

add_subdirectory(lib/EmberLib)

add_executable(EmberBrowser main.cpp)
target_link_libraries(EmberBrowser PRIVATE EmberLib++)