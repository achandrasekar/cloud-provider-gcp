load("@io_bazel_rules_go//go:def.bzl", "go_library")

go_library(
    name = "go_default_library",
    srcs = [
        "cert.go",
        "csr.go",
        "io.go",
        "pem.go",
        "server_inspection.go",
    ],
    importmap = "k8s.io/cloud-provider-gcp/vendor/k8s.io/client-go/util/cert",
    importpath = "k8s.io/client-go/util/cert",
    visibility = ["//visibility:public"],
    deps = [
        "//vendor/k8s.io/client-go/util/keyutil:go_default_library",
        "//vendor/k8s.io/utils/net:go_default_library",
    ],
)
