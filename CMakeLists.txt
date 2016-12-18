cmake_minimum_required(VERSION 2.6)
project(spectrums_processing)

add_executable(spectrums_processing main.cpp)

install(TARGETS spectrums_processing RUNTIME DESTINATION bin)
