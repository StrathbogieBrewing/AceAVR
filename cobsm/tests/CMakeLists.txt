cmake_minimum_required(VERSION 3.11)

project(cobsm)

add_executable(test_cobsm ../src/cobsm.c cobsm_test.c)
target_include_directories(test_cobsm PUBLIC ../include ../../acetest/include)



