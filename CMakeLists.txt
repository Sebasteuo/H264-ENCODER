cmake_minimum_required(VERSION 3.12)
project(h264simpleCoder_master)

set(CMAKE_CXX_STANDARD 14)

include_directories(src)

add_executable(h264simpleCoder_master
        src/CJOCh264bitstream.cpp
        src/CJOCh264bitstream.h
        src/CJOCh264encoder.cpp
        src/CJOCh264encoder.h
        src/h264simpleCoder.cpp)
