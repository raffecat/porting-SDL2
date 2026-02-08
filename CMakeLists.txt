add_library(Porting STATIC
    qrt_system.c
    qrt_services.c
)
target_include_directories(Porting PUBLIC ${CMAKE_CURRENT_SOURCE_DIR})

find_package(SDL2 REQUIRED)
target_link_libraries(Porting PRIVATE SDL2::SDL2)
