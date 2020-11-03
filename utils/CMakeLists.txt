if(BUILD_SHARED_LIBS)
  configure_file(
    ${CMAKE_CURRENT_SOURCE_DIR}/buildxyceplugin.in ${CMAKE_CURRENT_BINARY_DIR}/buildxyceplugin )
endif()
