project (spidev_test)
add_executable(spidev_test spidev_test.c)
target_link_libraries(spidev_test)
install(TARGETS spidev_test DESTINATION bin)

