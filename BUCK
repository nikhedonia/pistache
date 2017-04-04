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
  visibility = [
    'PUBLIC',
  ],
)
