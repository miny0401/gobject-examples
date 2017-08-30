aux_source_directory(. src)

add_executable(bank_account ${src} $<TARGET_OBJECTS:tap>)

target_link_libraries(bank_account glib-2.0 gobject-2.0)

set(EXECUTABLE_OUTPUT_PATH ${PROJECT_BINARY_DIR})
