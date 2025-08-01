droidcam_sources = [
  'droidcamsrc.c',
  'plugin.c'
]

shared_library('spa-droidcam',
  droidcam_sources,
  dependencies: [
    pipewire_dep,
    spa_dep,
    hybris_camera_dep,
    hybris_media_dep,
    android_headers_dep,
    opengl_dep,
    egl_dep,
    yuv_dep
  ],
  include_directories: include_directories('.'),
  install: true,
  install_dir: spa_plugins_install_dir
)