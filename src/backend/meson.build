# enable xrender
srcs += [ files('backend_common.c', 'xrender.c', 'backend.c') ]

# enable opengl
if get_option('opengl')
  srcs += [ files('gl/gl_common.c', 'gl/glx.c') ]
endif
