FILE(GLOB_RECURSE src "*.cpp" "*.h")
ADD_EXECUTABLE(Directional_Demo WIN32 ${src})
TARGET_LINK_LIBRARIES(Directional_Demo ${DEMO_LIBS})
