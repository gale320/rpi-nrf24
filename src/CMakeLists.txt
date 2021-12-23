file(GLOB SRC ./*.cpp)
add_library(nrf24 SHARED ${SRC})
target_link_libraries(nrf24 ${Glog_LIBS}  ${gflags_LIBS})