project('nx2elf', 'cpp', default_options: ['buildtype=plain', 'cpp_std=c++14', 'warning_level=0'])

executable(meson.project_name(),
  sources: files('elf_eh.cpp', 'nx2elf.cpp'),
  dependencies: dependency('liblz4'),
  install: true
)
