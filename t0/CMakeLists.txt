PROJECT(HELLO C)
SET(SRC hello.c)
MESSAGE(STATUS "This is binary directory : " ${HELLO_BINARY_DIR})
MESSAGE(STATUS "This is source directory : " ${HELLO_SOURCE_DIR})
ADD_EXECUTABLE(hello ${SRC})

