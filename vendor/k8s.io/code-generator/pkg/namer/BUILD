load("@io_bazel_rules_go//go:def.bzl", "go_library")

go_library(
    name = "go_default_library",
    srcs = ["tag-override.go"],
    importmap = "k8s.io/cloud-provider-gcp/vendor/k8s.io/code-generator/pkg/namer",
    importpath = "k8s.io/code-generator/pkg/namer",
    visibility = ["//visibility:public"],
    deps = [
        "//vendor/k8s.io/gengo/namer:go_default_library",
        "//vendor/k8s.io/gengo/types:go_default_library",
    ],
)
