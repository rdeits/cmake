project(pods-cmake)

file(GLOB cmake_files ${CMAKE_CURRENT_SOURCE_DIR}/*.cmake)
install(FILES ${cmake_files} DESTINATION share/cmake)

file(GLOB pl_files ${CMAKE_CURRENT_SOURCE_DIR}/*.pl)
install(FILES ${pl_files} DESTINATION share/cmake)
