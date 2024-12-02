load("@rules_rust//rust:defs.bzl", "rust_library", "rust_test")

package(default_visibility = ["//visibility:public"])

rust_library(
    name = "substring_library",
    srcs = ["src/lib.rs"],
    edition = "2021"
)

rust_test(
    name = "substring_library_test",
    srcs = ["src/lib.rs"],
    deps = [
        # Depend on the library on the above declaration
        ":substring_library",
    ],
    edition = "2021"
)