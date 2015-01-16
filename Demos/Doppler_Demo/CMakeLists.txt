FILE(GLOB_RECURSE src "*.cpp" "*.h")
ADD_EXECUTABLE(Doppler_Demo WIN32 ${src})
TARGET_LINK_LIBRARIES(Doppler_Demo ${DEMO_LIBS})
