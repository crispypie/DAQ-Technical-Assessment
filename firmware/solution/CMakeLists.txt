cmake_minimum_required(VERSION 3.22)

project(solution)

# Set C++ standard
set(CMAKE_CXX_STANDARD 17)
set(CMAKE_CXX_STANDARD_REQUIRED ON)

# Add dbcppp as a subdirectory
add_subdirectory(${CMAKE_SOURCE_DIR}/external/dbcppp ${CMAKE_BINARY_DIR}/dbcppp)

# Executable
add_executable(answer main.cpp)
target_include_directories(answer PRIVATE ${CMAKE_SOURCE_DIR}/external/dbcppp/src)

target_link_libraries(answer PRIVATE dbcppp)

if(NOT CMAKE_BUILD_TYPE)
  set(CMAKE_BUILD_TYPE Release)
endif()

if(CMAKE_BUILD_TYPE STREQUAL "Debug")
  add_definitions(-DDEBUG)
endif()


