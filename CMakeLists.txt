cmake_minimum_required(VERSION 3.16)
project(demo-project)

# Set C++17 standard
set(CMAKE_CXX_STANDARD 17)
set(CMAKE_CXX_STANDARD_REQUIRED True)

message("SSH_AUTH_SOCK: '$ENV{SSH_AUTH_SOCK}'")
