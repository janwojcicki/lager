load('//:buckaroo_macros.bzl', 'buckaroo_deps')

cxx_library(
  name = 'lager', 
  header_namespace = '', 
  exported_headers = subdir_glob([
    ('lagger', '**/*.hpp'),
  ]),
  srcs = glob([
    'src/**/*.cpp', 
  ]), 
  deps = buckaroo_deps(), 
  visibility = [
    'PUBLIC', 
  ], 
)

