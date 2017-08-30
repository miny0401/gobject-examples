aux_source_directory(. src)

add_executable(binary_tree ${src} $<TARGET_OBJECTS:tap>)

target_link_libraries(binary_tree glib-2.0 gobject-2.0)

set(EXECUTABLE_OUTPUT_PATH ${PROJECT_BINARY_DIR})
