cxx_library(
  name = 'googletest',
  header_namespace = '',
  srcs = [
    'googletest/src/gtest-all.cc',
    'googletest/src/gtest_main.cc',
  ],
  headers = subdir_glob([
    ('googletest', 'src/*.h'),
    ('googletest', 'src/*.cc'),
    ('googletest/include', '**/*.h'),
  ]),
  deps = [
    '//:pthread',
  ],
  exported_headers = subdir_glob([
    ('googletest/include', '**/*.h'),
  ]),
  preprocessor_flags = [
    '-U_STRICT_ANSI_',
  ],
  compiler_flags = [
  ],
  visibility = [
    'PUBLIC',
  ],
)