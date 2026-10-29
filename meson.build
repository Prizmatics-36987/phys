project(
  'phys',
  'cpp',
  version : '0.1',
  meson_version : '>= 1.3.0',
  default_options : ['warning_level=3', 'cpp_std=c++20'],
)

dependencies = [
  dependency('sfml-graphics')
]

sources = [
  'src/phys.cpp',
]

exe = executable(
  'phys',
  sources,
  install : true,
  dependencies : dependencies,
)

test('basic', exe)
