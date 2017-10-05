cxx_library(
  name = 'cctz',
  header_namespace = 'cctz',
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
  visibility = [
    'PUBLIC',
  ],
)
