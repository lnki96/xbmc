set(HEADERS audio_engine.h
            network.h)

if(NOT ENABLE_STATIC_LIBS)
  core_add_library(addons_kodi-addon-dev-kit_include_kodi_c-api)
endif()
