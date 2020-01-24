### Add source code for gtsam distortion models
target_sources(KimeraVIO PRIVATE
  "${CMAKE_CURRENT_LIST_DIR}/Cal3DS3.h"
  "${CMAKE_CURRENT_LIST_DIR}/Cal3FS2.h"
)
target_include_directories(KimeraVIO PRIVATE ${CMAKE_CURRENT_LIST_DIR})
