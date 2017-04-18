cxx_library(
  name = 'pistache',
  header_namespace = '',
  exported_headers = subdir_glob([
    ('include', '**/*.h'),
  ]),
  srcs = glob([
    'src/**/*.cc',
  ]),
  compiler_flags = [
    '-std=c++11',
  ],
  exported_platform_linker_flags = [
    ('.*linux.*', ['-lpthread']),
    ('.*osx.*', ['-lpthread']),
    ('default', ['-lpthread']),
  ],
  visibility = [
    'PUBLIC',
  ],
)
