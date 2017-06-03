cmake_minimum_required(VERSION 2.8.4)

project( JSMN C )

set(CMAKE_RUNTIME_OUTPUT_DIRECTORY ${JSMN_SOURCE_DIR}/bin/)

set(SOURCES jsmn.h jsmn.c)
add_library(JSMN STATIC ${SOURCES})
