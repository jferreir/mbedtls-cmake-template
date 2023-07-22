add_executable(hash main.c)
target_link_libraries(hash PRIVATE MbedTLS::mbedtls 
                                   MbedTLS::mbedcrypto
                                   MbedTLS::mbedx509)
