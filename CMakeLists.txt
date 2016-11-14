include_directories(lib)
add_definitions(-DRMT_USE_CUDA)
add_library(Remotery SHARED lib/remotery.c)
set_target_properties(Remotery PROPERTIES COMPILE_DEFINITIONS -DRMT_DLL)