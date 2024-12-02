load("@rules_rust//rust:defs.bzl", "rust_binary")

rust_binary(
    name = "rs_bazel",
    srcs = ["src/main.rs"],
    deps = [
        '//substring-library:substring_library'
    ],
    edition = "2021"
)