cmake_minimum_required(VERSION 3.7)

project(P372)

set(srcs InitializeNoise.c Noise.c NoiseMemory.c)

dirset(srcs Src/P372 ${srcs})

add_library(p372 MODULE ${srcs})
