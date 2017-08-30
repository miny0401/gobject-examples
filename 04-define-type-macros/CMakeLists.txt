aux_source_directory(. src)

add_executable(define_type_macros ${src})

target_link_libraries(define_type_macros glib-2.0 gobject-2.0)

set(EXECUTABLE_OUTPUT_PATH ${PROJECT_BINARY_DIR})
