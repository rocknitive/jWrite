cmake_minimum_required(VERSION 3.31)

project(
    jWrite
    LANGUAGES C
)

add_executable(${PROJECT_NAME} jWrite.c main.c)

#target_link_libraries(
#    ${PROJECT_NAME}
#    INTERFACE
#    rocknitive_printf
#)
#
#target_include_directories(
#    ${PROJECT_NAME}
#    INTERFACE
#    ../printf
#)

#target_compile_definitions(
#    ${PROJECT_NAME}
#    INTERFACE
#    JREAD_SINGLE_PRECISION
#    JWRITE_SINGLE_PRECISION
#)
