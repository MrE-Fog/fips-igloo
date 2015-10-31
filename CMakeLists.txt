#
# project: igloo
#
cmake_minimum_required(VERSION 2.8)
set(CMAKE_SOURCE_DIR "${CMAKE_SOURCE_DIR}/igloo")
set(FIPS_EXCEPTIONS ON CACHE BOOL "Enable C++ exceptions" FORCE)

fips_setup(PROJECT igloo)
fips_add_subdirectory(igloo)
fips_finish()
