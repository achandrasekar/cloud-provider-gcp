load("@io_bazel_rules_go//go:def.bzl", "go_library")

go_library(
    name = "go_default_library",
    srcs = ["internaloption.go"],
    importmap = "k8s.io/cloud-provider-gcp/vendor/google.golang.org/api/option/internaloption",
    importpath = "google.golang.org/api/option/internaloption",
    visibility = ["//visibility:public"],
    deps = [
        "//vendor/golang.org/x/oauth2/google:go_default_library",
        "//vendor/google.golang.org/api/internal:go_default_library",
        "//vendor/google.golang.org/api/option:go_default_library",
    ],
)
