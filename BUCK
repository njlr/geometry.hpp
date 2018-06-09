BUCKAROO_DEPS = []

prebuilt_cxx_library(
  name = 'geometry', 
  header_namespace = 'mapbox', 
  header_only = True,
  exported_headers = subdir_glob([
    ('include/mapbox', '**/*.hpp'),
  ]),
  deps = BUCKAROO_DEPS, 
  visibility = [
    'PUBLIC', 
  ]
)
