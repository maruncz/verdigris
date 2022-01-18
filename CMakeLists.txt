cmake_minimum_required(VERSION 3.5)

project(verdigris LANGUAGES CXX)

set(VERDIGRIS_HEADERS
    wobjectcpp.h
    wobjectdefs.h
    wobjectimpl.h
    )

add_library(verdigris INTERFACE)
target_include_directories(verdigris INTERFACE ${CMAKE_CURRENT_SOURCE_DIR}/src)

