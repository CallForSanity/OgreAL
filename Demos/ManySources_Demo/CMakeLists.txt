FILE(GLOB_RECURSE src "*.cpp" "*.h")
ADD_EXECUTABLE(ManySources_Demo WIN32 ${src})
TARGET_LINK_LIBRARIES(ManySources_Demo ${DEMO_LIBS})
