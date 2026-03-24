cmake_minimum_required(VERSION 4.0)
project(Calcolatrice C)

set(CMAKE_C_STANDARD 11)

add_executable(Calcolatrice main.c
        operazioni.h
        operazioni.c)
