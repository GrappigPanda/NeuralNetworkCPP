add_library(SMS matrix.cpp arithmetic.cpp)
target_include_directories (SMS PUBLIC ${CMAKE_CURRENT_SOURCE_DIR})