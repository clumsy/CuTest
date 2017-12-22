cmake_minimum_required(VERSION 3.8)
project(cutest)

set(CMAKE_C_STANDARD 11)

set(SOURCE_FILES CuTest.h)
set(TEST_FILES test/CuTestSample.c test/AllTests.c)

add_executable(AllTests ${SOURCE_FILES} ${TEST_FILES})
