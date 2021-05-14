cmake_minimum_required(VERSION 3.10.2)
project(poo1_PC1_lab106_v2021_1)

set(CMAKE_CXX_STANDARD 17)
set(CMAKE_RUNTIME_OUTPUT_DIRECTORY ${CMAKE_CURRENT_BINARY_DIR}/${OUTPUT_DEBUG})
#set(CMAKE_CXX_FLAGS "-m64 -Wa,-mbig-obj")
if(UNIX AND NOT APPLE)
    set(CMAKE_CXX_FLAGS -pthread)
endif()

add_executable(poo1_PC1_lab106_v2021_1
        main.cpp 
        p1.h p1.cpp
        p2.h p2.cpp
        p3.h p3.cpp
        test_1_1.cpp
        test_2_1.cpp
        test_3_1.cpp
  )

configure_file(test_1_1.in ${CMAKE_RUNTIME_OUTPUT_DIRECTORY} COPYONLY)
configure_file(test_2_1.in ${CMAKE_RUNTIME_OUTPUT_DIRECTORY} COPYONLY)
configure_file(test_3_1.in ${CMAKE_RUNTIME_OUTPUT_DIRECTORY} COPYONLY)
