include_directories(lib)
add_definitions(-DRMT_USE_CUDA)
add_library(remotery SHARED lib/remotery.c)
set_target_properties(remotery PROPERTIES COMPILE_DEFINITIONS -DRMT_DLL)