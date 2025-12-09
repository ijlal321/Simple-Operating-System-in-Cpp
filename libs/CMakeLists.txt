
add_library(MyLib my_lib.cpp my_lib.h)

target_include_directories(MyLib PUBLIC ${CMAKE_CURRENT_SOURCE_DIR})