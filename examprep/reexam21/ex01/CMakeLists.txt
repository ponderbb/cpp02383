cmake_minimum_required(VERSION 3.0.0)
project(may21ex01 VERSION 0.1.0)

include(CTest)
enable_testing()

add_executable(may21ex01 ex01-library.cpp ex01-main.cpp)

set(CPACK_PROJECT_NAME ${PROJECT_NAME})
set(CPACK_PROJECT_VERSION ${PROJECT_VERSION})
include(CPack)
