include_directories(${include_directories} CHECK_INCLUDES)

add_custom_target(check COMMAND ${CMAKE_CTEST_COMMAND})

add_subdirectory(array)
add_subdirectory(bstring)
add_subdirectory(channel)
add_subdirectory(event)
add_subdirectory(log)
add_subdirectory(metric)
add_subdirectory(option)
add_subdirectory(pool)
add_subdirectory(rbuf)
add_subdirectory(ring_array)
add_subdirectory(time)
