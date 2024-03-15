cmake_minimum_required(VERSION 3.21)

project(WebLib CXX)

set(Source
    "src/WebLib.cpp"
)

set(IncludeDirs
    "include/"
)

add_library(${PROJECT_NAME} ${Source})
target_include_directories(${PROJECT_NAME} PUBLIC ${IncludeDirs})