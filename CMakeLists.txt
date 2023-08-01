cmake_minimum_required(VERSION 3.25)
project(Lab3)

set(CMAKE_CXX_STANDARD 17)
set(SDL_INCLUDE_DIR C:/SDL/include)
set(SDL2_LIB_DIR C:/SDL/lib/x64)

include_directories(${SDL_INCLUDE_DIR})
link_directories(${SDL2_LIB_DIR})
include_directories("C:/MinGW/include")

add_executable(Lab3 main.cpp)

target_link_libraries(Lab3 SDL2main SDL2)
