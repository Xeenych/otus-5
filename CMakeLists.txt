cmake_minimum_required(VERSION 3.5)
set(CMAKE_EXPORT_COMPILE_COMMANDS ON)

project(otus-5 LANGUAGES CXX)
#add_compile_options(-Werror)
#add_compile_options(-Wall)
#add_compile_options(-Wextra)
#add_compile_options(-Warray-bounds)
#add_compile_options(-Weffc++)

add_executable(otus-5 src/main.cpp)
set_target_properties(otus-5 PROPERTIES CXX_STANDARD 20 CXX_STANDARD_REQUIRED ON)

