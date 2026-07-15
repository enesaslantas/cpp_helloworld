cmake_minimum_required(VERSION 3.10)


project(BenimSacmaProgramim VERSION 1.0)


set(CMAKE_CXX_STANDARD 17)
set(CMAKE_CXX_STANDARD_REQUIRED ON)

set(SOURCE_FILES
    main.cpp
    log.cpp
)

add_executable(program ${SOURCE_FILES})