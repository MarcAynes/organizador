cmake_minimum_required(VERSION 3.13)
project(untitled C)

set(CMAKE_C_STANDARD 90)


add_executable(untitled main.c logic/utils/utils.c logic/menu/menu.c logic/functions/functions.c model/list/list.c model/destination/destination.c)