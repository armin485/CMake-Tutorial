
include_directories("${PROJECT_SOURCE_DIR}/src")
add_subdirectory(src)

add_executable(Tutorial src/main.cc)
target_link_libraries(Tutorial Func)
