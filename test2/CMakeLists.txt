
include_directories("${PROJECT_SOURCE_DIR}/funcs")
add_subdirectory(funcs)

add_executable(Tutorial main.cc)
target_link_libraries(Tutorial Func)
