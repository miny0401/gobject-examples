aux_source_directory(. src)

add_executable(point_inheritance ${src})

target_link_libraries(point_inheritance glib-2.0 gobject-2.0)

set(EXECUTABLE_OUTPUT_PATH ${PROJECT_BINARY_DIR})
