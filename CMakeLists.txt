cmake_minimum_required(VERSION 3.18)

project(nrf24 CXX)

include(cmake/option.cmake)
include(cmake/glog.cmake)
include(cmake/glog.cmake)
include(cmake/opencv.cmake)
include(cmake/boost.cmake)

include_directories(src)
link_directories(/usr/local/lib )

add_subdirectory(src)
add_subdirectory(app)