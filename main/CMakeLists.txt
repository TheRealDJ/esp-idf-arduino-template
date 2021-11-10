# Edit following two lines to set component requirements (see docs)
set(COMPONENT_REQUIRES )
set(COMPONENT_PRIV_REQUIRES )

list(APPEND COMPONENT_SRCS "idf-arduino-template.cpp")

string(APPEND CMAKE_CXX_FLAGS " -Wno-unused-but-set-parameter")

register_component()
