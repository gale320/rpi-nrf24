add_executable(scan scanner.cpp)
target_link_libraries(scan nrf24)

add_executable(receive receiver.cpp)
target_link_libraries(receive nrf24)

add_executable(trans receiver.cpp)
target_link_libraries(trans nrf24)
