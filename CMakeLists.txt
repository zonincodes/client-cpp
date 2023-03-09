cmake_minimum_required(VERSION 3.0)
project(demo)

set(CMAKE_CXX_STANDARD 11)
set(CMAKE_CXX_STANDARD_REQUIRED ON)

add_executable(demo main.cpp)

target_include_directories(${PROJECT_NAME}
    PUBLIC src
)

target_link_directories(${PROJECT_NAME} 
    PUBLIC src
)