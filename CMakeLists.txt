cmake_minimum_required(VERSION 3.28.0)
project(Education VERSION 0.1.0 LANGUAGES C CXX)

include(CTest)
enable_testing()

add_executable(main.out main.cpp)

set(CPACK_PROJECT_NAME ${PROJECT_NAME})
set(CPACK_PROJECT_VERSION ${PROJECT_VERSION})
include(CPack)