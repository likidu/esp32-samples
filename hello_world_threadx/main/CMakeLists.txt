idf_component_register(SRCS "hello_world_threadx.c" INCLUDE_DIRS ".")

# Import threadx library targets
# add_subdirectory(lib/threadx)

# Link threadx libraries to main component
# target_link_libraries(${COMPONENT_LIB} PUBLIC threadx)