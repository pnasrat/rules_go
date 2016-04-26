load("@io_bazel_rules_go//go:def.bzl", "go_prefix", "go_library")

go_prefix("golang.org/x/net/context/ctxhttp")

go_library(
    name = "go_default_library",
    deps = ["//vendor/golang_org/x/net/context:go_default_library"],
    srcs = [
        "ctxhttp.go",
        "cancelreq.go",
    ]
)
