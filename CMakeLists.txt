cmake_minimum_required(VERSION 3.10)

# set the project name
project(fast-smb-lzss)

set(CMAKE_C_STANDARD 17)
set(CMAKE_CXX_STANDARD 20)
set(CMAKE_EXPORT_COMPILE_COMMANDS ON)

# add the executable
add_executable(SMB_LZ_TOOL
    src/main.cpp)
