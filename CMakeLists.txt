cmake_minimum_required(VERSION 3.16)

include($ENV{IDF_PATH}/tools/cmake/project.cmake)
project(clockwise)

target_add_frogfs(clockwise.elf)
