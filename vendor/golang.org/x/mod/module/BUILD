load("@io_bazel_rules_go//go:def.bzl", "go_library")

go_library(
    name = "go_default_library",
    srcs = ["module.go"],
    importmap = "k8s.io/cloud-provider-gcp/vendor/golang.org/x/mod/module",
    importpath = "golang.org/x/mod/module",
    visibility = ["//visibility:public"],
    deps = [
        "//vendor/golang.org/x/mod/semver:go_default_library",
        "//vendor/golang.org/x/xerrors:go_default_library",
    ],
)
