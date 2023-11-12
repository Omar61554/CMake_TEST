# cmake

cmake_minimum_required(VERSION 3.28.0)
project(cmake_test)
set(SRC_Files 
test.cpp
LIB/lib.cpp)
message("SRC_Files: ${SRC_Files}")
add_executable(cmake_test ${SRC_Files})
target_include_directories(cmake_test PUBLIC LIB/ )
