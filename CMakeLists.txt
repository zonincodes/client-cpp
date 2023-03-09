cmake_minimum_required(VERSION 3.33)

project(client_one)
include_directories(${PROJECT_SOURCE_DIR})

target_include_directories(${PROJECT_NAME}
    PUBLIC src
)

target_link_directories(${PROJECT_NAME}
    PUBLIC src
)