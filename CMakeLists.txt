cmake_minimum_required(VERSION 2.8)

project(gobject-example)

set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -g")

include_directories("/usr/include/glib-2.0")
include_directories("/usr/lib/glib-2.0/include")

include_directories("tap")

add_subdirectory(tap)
add_subdirectory(01-media-from-book)
add_subdirectory(02-point-inheritance)
add_subdirectory(03-order-of-callbacks)
add_subdirectory(04-define-type-macros)
add_subdirectory(05-bank-account)
add_subdirectory(06-binary-tree)
add_subdirectory(07-currency-interfaces)
