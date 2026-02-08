add_library(Porting
    qrt_system.c
    qrt_services.c
)
target_include_directories(Porting PRIVATE ${CMAKE_CURRENT_SOURCE_DIR})
