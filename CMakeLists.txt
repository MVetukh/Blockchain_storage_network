cmake_minimum_required(VERSION 3.28)
project(Blockchain_storage_network)

set(CMAKE_CXX_STANDARD 17)

add_executable(Blockchain_storage_network main.cpp
        src/blockchain/Block.h
        src/blockchain/Block.cpp)
