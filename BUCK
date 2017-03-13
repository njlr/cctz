cxx_library(
  name = 'cctz',
  header_namespace = '',
  exported_headers = subdir_glob([
    ('include', '*.h'),
  ]),
  headers = subdir_glob([
    ('src', '*.h'),
  ]),
  srcs = glob([
    'src/*.cc',
  ],
  excludes = glob([
    'src/*_test.cc',
  ])),
  compiler_flags = [
    '-std=c++11',
  ],
  visibility = [
    'PUBLIC',
  ],
)
