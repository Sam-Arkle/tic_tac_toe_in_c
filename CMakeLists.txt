cmake_minimum_required(VERSION 3.23)
project(tic_tac_toe C)

set(CMAKE_C_STANDARD 99)

add_executable(tic_tac_toe main.c tictactoe.c tictactoe.h)
