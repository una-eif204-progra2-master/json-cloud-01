cmake_minimum_required(VERSION 3.17)
project(cloud_file_test)

set(CMAKE_CXX_STANDARD 14)

include_directories(src)
include_directories(lib/curlpp/include)

add_subdirectory(src)
## add_subdirectory(tst)

## Use next line if you are going to use Google Test
## add_subdirectory(lib/googletest)
add_subdirectory(lib/curlpp)