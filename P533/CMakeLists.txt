cmake_minimum_required(VERSION 3.7)

project(P533)

set(srcs Between7000kmand9000km.c ELayerScreeningFrequency.c Magfit.c
  MedianSkywaveFieldStrengthShort.c ReadIonParameters.c
  CalculateCPParameters.c Geometry.c MUFBasic.c P533.c
  MUFOperational.c ReadP1239.c CircuitReliability.c InitializePath.c
  MedianAvailableReceiverPower.c ReadType13.c InputDump.c
  MedianSkywaveFieldStrengthLong.c MUFVariability.c PathMemory.c
  ValidatePath.c)

dirset(srcs Src/P533 ${srcs})

add_library(p533 MODULE ${srcs})
