cxx_library(
  name = 'cctz',
  header_namespace = '',
  exported_headers = subdir_glob([
    ('include', '**/*.h'),
  ]),
  headers = subdir_glob([
    ('src', '**/*.h'),
  ]),
  srcs = glob([
    'src/**/*.cc',
  ],
  excludes = glob([
    'src/benchmarks.cc',
    'src/**/*_test.cc',
  ])),
  visibility = [
    'PUBLIC',
  ],
)
