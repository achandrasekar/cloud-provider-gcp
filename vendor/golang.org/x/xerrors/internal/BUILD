load("@io_bazel_rules_go//go:def.bzl", "go_library")

go_library(
    name = "go_default_library",
    srcs = ["internal.go"],
    importmap = "k8s.io/cloud-provider-gcp/vendor/golang.org/x/xerrors/internal",
    importpath = "golang.org/x/xerrors/internal",
    visibility = ["//vendor/golang.org/x/xerrors:__subpackages__"],
)
