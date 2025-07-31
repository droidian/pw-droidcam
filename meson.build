project('pw-droidcam', 'c', version: '0.1', default_options: ['c_std=c99'])

pipewire_dep = dependency('libpipewire-0.3', required: true)
spa_dep = dependency('libspa-0.2', required: true)
android_headers_dep = dependency('android-headers', required: true)
hybris_camera_dep   = dependency('libcamera', required: true)
hybris_media_dep    = dependency('libmedia', required: true)
opengl_dep = dependency('gl', required: true)
egl_dep = dependency('egl', required: true)

add_project_arguments('-D_GNU_SOURCE', language: 'c')

spa_plugins_install_dir = join_paths(get_option('prefix'), 'lib', 'spa-0.2', 'plugins')

subdir('spa/plugins/droidcam')