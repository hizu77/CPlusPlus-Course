add_library(OperationController STATIC OperationController.h OperationController.cpp)

target_include_directories(OperationController PUBLIC ${CMAKE_CURRENT_SOURCE_DIR})

target_link_libraries(OperationController PUBLIC FileInfo)
