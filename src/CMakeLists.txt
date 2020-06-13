cmake_minimum_required(VERSION 3.16)

project(rconhttp
        VERSION 1.0.0
        DESCRIPTION "RCON 2 HTTP Bridge"
        HOMEPAGE_URL https://github.com/Emseers/rcon2http
        LANGUAGES CXX)

set(CMAKE_CXX_STANDARD 20)

add_executable(rconhttp main.cpp)