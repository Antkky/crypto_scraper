cmake_minimum_required(VERSION 3.10)
project(CryptoScraper)

set(CMAKE_CXX_STANDARD 17)
set(CMAKE_CXX_STANDARD_REQUIRED True)

add_executable(CryptoScraper main.cpp)

include_directories(${CMAKE_SOURCE_DIR}/include)
target_link_libraries(CryptoScraper PRIVATE m)
