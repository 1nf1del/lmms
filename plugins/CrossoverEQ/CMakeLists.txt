INCLUDE(BuildPlugin)

BUILD_PLUGIN(crossovereq CrossoverEQ.cpp CrossoverEQControls.cpp CrossoverEQControlDialog.cpp MOCFILES CrossoverEQControls.h CrossoverEQControlDialog.h EMBEDDED_RESOURCES "${CMAKE_CURRENT_SOURCE_DIR}/*.png")
