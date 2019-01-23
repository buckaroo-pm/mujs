cxx_library(
  name = 'mujs',
  header_namespace = '',
  srcs = glob(['*.c'], exclude=['one.c', 'main.c']),
  exported_headers = glob(['*.h']),
  visibility = ['PUBLIC']
)

cxx_binary(
  name = 'mujs-cli',
  srcs = ['main.c'],
  deps = [':mujs'],
  visibility = ['PUBLIC']
)
