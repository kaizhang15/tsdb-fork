include_directories(..)
aux_source_directory(. DIR_LIB_SRCS)

add_library (Base ${DIR_LIB_SRCS})