load("@io_bazel_rules_go//go:def.bzl", "go_library")

go_library(
    name = "go_default_library",
    srcs = [
        "join.go",
        "vfs.go",
    ],
    importmap = "k8s.io/cloud-provider-gcp/vendor/github.com/cyphar/filepath-securejoin",
    importpath = "github.com/cyphar/filepath-securejoin",
    visibility = ["//visibility:public"],
    deps = ["//vendor/github.com/pkg/errors:go_default_library"],
)
