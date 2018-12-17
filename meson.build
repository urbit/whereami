project('whereami', 'c', version : '1.0.0')

version = meson.project_version()

sources = ['src/whereami.c']
inc = include_directories('src/')

lib = static_library('whereami', sources: sources, version: version,
include_directories : inc,
c_args: [],
install: false)

libwhereami_dep = declare_dependency(include_directories : inc,
  link_with : lib)
