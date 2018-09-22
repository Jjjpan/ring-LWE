cmake_minimum_required(VERSION 3.12)
project(ring_LWE C)

set(CMAKE_C_STANDARD 11)

include_directories(.)

add_executable(ring_LWE
        global.h
        luts.c
        luts.h
        lwe.c
        lwe.h
        lwe_original.c
        lwe_original.h
        main.c)
