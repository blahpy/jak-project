add_subdirectory(util)
add_subdirectory(goos)
add_subdirectory(listener)
add_subdirectory(emitter)

add_executable(goalc main.cpp)

target_link_libraries(goalc util goos)