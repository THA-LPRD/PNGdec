FILE(GLOB SOURCES "src/*.c")

idf_component_register(SRCS ${SOURCES}
                       INCLUDE_DIRS "src"
                       REQUIRES "arduino-esp32")
