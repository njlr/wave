include_defs('//BUCKAROO_DEPS')

cxx_library(
  name = 'boost-wave',
  header_namespace = 'boost',
  exported_headers = subdir_glob([
    ('include/boost', '**/*.hpp'),
  ]),
  srcs = glob([
    'src/**/*.cpp',
  ]),
  compiler_flags = [
    '-DBOOST_HAS_THREADS',
    '-DBOOST_THREAD_USE_LIB',
  ],
  visibility = [
    'PUBLIC',
  ],
  deps = BUCKAROO_DEPS,
)
