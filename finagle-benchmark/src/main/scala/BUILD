benchmark(name='scala',
  dependencies=[
    pants('3rdparty:caliper'),
    pants('3rdparty:scala-library'),
    pants('finagle/finagle-core'),
    pants('finagle/finagle-memcached'),
    pants('finagle/finagle-ostrich4'),
    pants('finagle/finagle-stats'),
    pants('finagle/finagle-zipkin'),
    pants('finagle/finagle-swift'),
    pants('finagle/finagle-benchmark/src/main/thrift:thrift-scala'),
  ],
  sources=rglobs('*.scala')
)
