add_library(choingo-board STATIC board.cpp)
target_include_directories(choingo-board PUBLIC ${CMAKE_CURRENT_SOURCE_DIR}/.. PRIVATE ${CMAKE_CURRENT_SOURCE_DIR})