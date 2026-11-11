cmake_minimum_required(VERSION 3.25)
project(MeuRender LANGUAGES C CXX)

set(CMAKE_CXX_STANDARD 20)
set(CMAKE_CXX_STANDARD_REQUIRED ON)

add_executable(meu_render src/main.cpp)