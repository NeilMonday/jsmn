cmake_minimum_required(VERSION 2.8.4)

project( JSMN C )

set(SOURCES jsmn.h jsmn.c)
add_library(JSMN STATIC ${SOURCES})

install(TARGETS JSMN 
    ARCHIVE DESTINATION .)
