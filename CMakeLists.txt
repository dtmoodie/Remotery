
add_definitions(-DRMT_DLL)
add_definitions(-DRMT_USE_CUDA)
add_library(remotery SHARED lib/Remotery.h lib/Remotery.c)