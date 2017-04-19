cmake_minimum_required(VERSION 3.6)
project(Project3)

set(CMAKE_CXX_STANDARD 11)

set(SOURCE_FILES nn.cpp)
add_executable(Project3 ${SOURCE_FILES})
configure_file(BeamA.dat ${CMAKE_CURRENT_BINARY_DIR}/BeamA.dat COPYONLY)
configure_file(BeamB.dat ${CMAKE_CURRENT_BINARY_DIR}/BeamB.dat COPYONLY)