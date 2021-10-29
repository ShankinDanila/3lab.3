cmake_minimum_required(VERSION 3.20)
project(3lab.3)

set(CMAKE_CXX_STANDARD 17)

add_subdirectory(Class_Table)
include_directories(Class_Table)

set(dialog Dialog/main.cpp Dialog/Dialog.cpp Dialog/Dialog.h)

add_executable(Lab3_Dialog ${dialog})

target_link_libraries(Lab3_Dialog 3lab.3)