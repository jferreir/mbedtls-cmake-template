message(STATUS "Fetching mbedtls...")

# https://discourse.cmake.org/t/what-is-the-correct-way-to-set-options-of-a-project-before-fetch-content/268/2
set(ENABLE_PROGRAMS OFF CACHE INTERNAL "Turn off programs")
set(ENABLE_TESTING OFF CACHE INTERNAL "Turn off tests")

FetchContent_MakeAvailable(mbedtls)
