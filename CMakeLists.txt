cmake_minimum_required( VERSION 2.6 )
project( algorithm )

include_directories( "include" )
include_directories( "." )

#add_executable(LRU_cache "LRU_cache.cpp")

file( GLOB APP_SOURCES LRU_cache.cpp )
SET( CMAKE_CXX_FLAGS  "${CMAKE_CXX_FLAGS} /FI\"alg_vs.h ) 
message( ${CMAKE_CXX_FLAGS} )
