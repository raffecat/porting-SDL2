add_library(Porting STATIC
    qrt_system.c
    qrt_services.c
)
target_include_directories(Porting PUBLIC ${CMAKE_CURRENT_SOURCE_DIR})
