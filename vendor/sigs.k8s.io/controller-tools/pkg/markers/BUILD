load("@io_bazel_rules_go//go:def.bzl", "go_library")

go_library(
    name = "go_default_library",
    srcs = [
        "collect.go",
        "doc.go",
        "help.go",
        "parse.go",
        "reg.go",
        "regutil.go",
        "zip.go",
    ],
    importmap = "k8s.io/cloud-provider-gcp/vendor/sigs.k8s.io/controller-tools/pkg/markers",
    importpath = "sigs.k8s.io/controller-tools/pkg/markers",
    visibility = ["//visibility:public"],
    deps = ["//vendor/sigs.k8s.io/controller-tools/pkg/loader:go_default_library"],
)
