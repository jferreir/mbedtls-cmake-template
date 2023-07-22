include(FetchContent)

# mbedtls
FetchContent_Declare(
  mbedtls
  URL https://github.com/Mbed-TLS/mbedtls/archive/refs/tags/v3.4.0.tar.gz
  URL_HASH SHA256=1b899f355022e8d02c4d313196a0a16af86c5a692456fa99d302915b8cf0320a
)
add_subdirectory(mbedtls)

