cmake_minimum_required(VERSION 3.10)

project(docpp)

set(CMAKE_CXX_STANDARD 17)

set(FILES src/*)

#Other rules to be added here 

add_library(docpp ${FILES})