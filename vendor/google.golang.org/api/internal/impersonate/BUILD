load("@io_bazel_rules_go//go:def.bzl", "go_library")

go_library(
    name = "go_default_library",
    srcs = ["impersonate.go"],
    importmap = "k8s.io/cloud-provider-gcp/vendor/google.golang.org/api/internal/impersonate",
    importpath = "google.golang.org/api/internal/impersonate",
    visibility = ["//vendor/google.golang.org/api:__subpackages__"],
    deps = ["//vendor/golang.org/x/oauth2:go_default_library"],
)
