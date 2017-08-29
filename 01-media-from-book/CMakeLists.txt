aux_source_directory(. src)

include_directories("/usr/include/glib-2.0")
include_directories("/usr/lib/glib-2.0/include")

add_executable(media_from_book ${src})

target_link_libraries(media_from_book glib-2.0 gobject-2.0)

set(EXECUTABLE_OUTPUT_PATH ${PROJECT_BINARY_DIR})