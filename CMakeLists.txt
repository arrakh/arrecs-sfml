cmake_minimum_required(VERSION 3.24)
project(arrecs-module-name)

set(CMAKE_CXX_STANDARD 17)

add_library(arrecs-module-name arrecs-module-name.cpp arrecs-module-name.h)

include_directories("../arrecs")

target_link_libraries(arrecs-module-name PRIVATE arrecs)