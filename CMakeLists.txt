cmake_minimum_required(VERSION 3.10)

# set the project name
project(fast-smb-lzss)

set(CMAKE_C_STANDARD 11)

# add the executable
add_executable(fast-smb-lzss
    src/main.c)
