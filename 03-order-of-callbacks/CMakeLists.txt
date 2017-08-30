aux_source_directory(. src)

add_executable(order_of_callbacks ${src})

target_link_libraries(order_of_callbacks glib-2.0 gobject-2.0)

set(EXECUTABLE_OUTPUT_PATH ${PROJECT_BINARY_DIR})
