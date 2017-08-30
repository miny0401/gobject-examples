aux_source_directory(. src)

add_executable(currency_interfaces ${src} $<TARGET_OBJECTS:tap>)

target_link_libraries(currency_interfaces glib-2.0 gobject-2.0)

set(EXECUTABLE_OUTPUT_PATH ${PROJECT_BINARY_DIR})
