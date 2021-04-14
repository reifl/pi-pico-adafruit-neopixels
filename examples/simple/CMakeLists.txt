add_executable(simple
        simple.cpp
        )

target_link_libraries(simple pico_stdlib pico_neopixel)

# create map/bin/hex file etc.
pico_add_extra_outputs(simple)
