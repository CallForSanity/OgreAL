FILE(GLOB_RECURSE src "*.cpp" "*.h")
ADD_EXECUTABLE(MultiChannel_Demo WIN32 ${src})
TARGET_LINK_LIBRARIES(MultiChannel_Demo ${DEMO_LIBS})
