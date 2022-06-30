```
$ bazel build --config=remote @bazel_diff//:bazel-diff
INFO: Invocation ID: ab2cc2d6-8343-4b45-9695-8d18f951cf2c
INFO: Streaming build results to: https://app.buildbuddy.io/invocation/ab2cc2d6-8343-4b45-9695-8d18f951cf2c
INFO: Analyzed target @bazel_diff//:bazel-diff (32 packages loaded, 976 targets configured).
INFO: Found 1 target...
INFO: From KotlinCompile @bazel_diff//cli:cli-lib { kt: 31, java: 0, srcjars: 0 } for k8:
WARNING: An illegal reflective access operation has occurred
WARNING: Illegal reflective access by io.bazel.kotlin.builder.toolchain.KotlinToolchain$JDepsInvoker (file:/buildbuddy/remotebuilds/12596dea-3e62-4e39-adea-3c1bc4fe0c84/bazel-out/host/bin/external/io_bazel_rules_kotlin/src/main/kotlin/build.runfiles/io_bazel_rules_kotlin/src/main/kotlin/kotlin_worker.jar) to method com.sun.tools.jdeps.Main.run(java.lang.String[],java.io.PrintWriter)
WARNING: Please consider reporting this to the maintainers of io.bazel.kotlin.builder.toolchain.KotlinToolchain$JDepsInvoker
WARNING: Use --illegal-access=warn to enable warnings of further illegal reflective access operations
WARNING: All illegal access operations will be denied in a future release
warning: '-Xuse-experimental' is deprecated and will be removed in a future release

Target @bazel_diff//cli:bazel-diff up-to-date:
  bazel-bin/external/bazel_diff/cli/bazel-diff.jar
  bazel-bin/external/bazel_diff/cli/bazel-diff
INFO: Elapsed time: 33.368s, Critical Path: 25.25s
INFO: 47 processes: 8 remote cache hit, 11 internal, 28 remote.
INFO: Streaming build results to: https://app.buildbuddy.io/invocation/ab2cc2d6-8343-4b45-9695-8d18f951cf2c
INFO: Build completed successfully, 47 total actions
```