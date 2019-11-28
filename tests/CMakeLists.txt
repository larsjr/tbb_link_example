include_directories(${CMAKE_SOURCE_DIR}/include)
add_executable(tests tests.cpp)

target_link_libraries(tests ${CMAKE_BINARY_DIR}/project1/libproject1.so)

