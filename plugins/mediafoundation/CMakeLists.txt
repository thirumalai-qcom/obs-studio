cmake_minimum_required(VERSION 3.28...3.30)

if(WIN32 AND CMAKE_SYSTEM_PROCESSOR MATCHES "ARM64")
    add_subdirectory(encoder)
endif()
