include_directories(${CMAKE_SOURCE_DIR}/include)
add_library(project1 SHARED project1.cpp project1.h)

target_link_libraries(project1 ${CMAKE_SOURCE_DIR}/lib/libtbbmalloc_proxy.so.2 ${CMAKE_SOURCE_DIR}/lib/libtbbmalloc.so.2)

