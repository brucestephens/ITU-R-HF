cmake_minimum_required(VERSION 3.7)

project(ITU-R-HF LANGUAGES C)

include_directories(BEFORE Common)
set(CMAKE_RUNTIME_OUTPUT_DIRECTORY ${CMAKE_BINARY_DIR}/bin)
set(CMAKE_LIBRARY_OUTPUT_DIRECTORY ${CMAKE_BINARY_DIR}/bin)

set(CMAKE_C_STANDARD 99)

set(CMAKE_EXPORT_COMPILE_COMMANDS on)

include(dirset.cmake)

add_subdirectory(P533)
add_subdirectory(P372)
# add_subdirectory(ITURHFProp)
