cc_library(
  name = 'lib',
  srcs = [
    'bench.c',
    'datagen.c',
    'lz4io.c',
  ],
  deps = [
    '//lz4/lib:lz4',
  ]
)

cc_binary(
  name = 'datagencli',
  srcs = [
    'datagencli.c',
  ],
  deps = [
    ':lib',
  ]
)

cc_binary(
  name = 'frametest',
  srcs = [
    'frametest.c',
  ],
  deps = [
    ':lib',
  ]
)

cc_binary(
  name = 'fullbench',
  srcs = [
    'fullbench.c',
  ],
  deps = [
    ':lib',
  ]
)

cc_binary(
  name = 'fuzzer',
  srcs = [
    'fuzzer.c',
  ],
  deps = [
    ':lib',
  ]
)

cc_binary(
  name = 'lz4cli',
  srcs = [
    'lz4cli.c',
  ],
  deps = [
    ':lib',
  ]
)
