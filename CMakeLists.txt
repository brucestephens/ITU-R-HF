cmake_minimum_required(VERSION 3.7)

project(ITU-R-HF LANGUAGES C)

set(CMAKE_C_STANDARD 99)

include(dirset.cmake)

add_subdirectory(P533)
add_subdirectory(P372)
# add_subdirectory(ITURHFProp)
