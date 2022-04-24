add_library(Lib_CLI
    src/cli.c)

target_include_directories(Lib_CLI PUBLIC "${CMAKE_CURRENT_SOURCE_DIR}/inc")