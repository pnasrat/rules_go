package(
    default_visibility = ["//visibility:public"],
)

load("//go:def.bzl", "go_binary", "go_library", "go_test")

go_library(
    name = "go_default_library",
    srcs = [
        "lib.go",
    ],
    deps = [
        "//examples/vendor/github_com/user/vendored:go_default_library",
        "//examples/vendor/golang_org/x/net/context:go_default_library",
    ],
)

go_test(
    name = "lib_test",
    srcs = [
        "lib_test.go",
    ],
    library = ":go_default_library",
)
