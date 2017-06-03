cmake_minimum_required(VERSION 2.8.4)

project( JSMN C )
set(HEADERS jsmn.h)
set(SOURCES ${HEADERS} jsmn.c)
add_library(JSMN STATIC ${SOURCES})

install(TARGETS JSMN 
    ARCHIVE DESTINATION lib)

install(FILES ${HEADERS} 
    DESTINATION include)
