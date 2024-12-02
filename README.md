# Source
https://earthly.dev/blog/bazel-with-rust/

# Command

## Creat project
```shell
cargo new rs-bazel
cargo new --lib substring-library
```

## Build and run compiled binary
```shell
# bazel run //package:target
bazel run //:rs_bazel
```

## Build target
```shell
bazel build //:rs_bazel
```

## Test
```shell
# bazel test //package:target
bazel test //substring-library:substring_library_test
```
