load("@io_bazel_rules_go//go:def.bzl", "go_library")

go_library(
    name = "go_default_library",
    srcs = [
        "adaptor.go",
        "doc.go",
        "errors.go",
        "fmt.go",
        "format.go",
        "frame.go",
        "wrap.go",
    ],
    importmap = "k8s.io/cloud-provider-gcp/vendor/golang.org/x/xerrors",
    importpath = "golang.org/x/xerrors",
    visibility = ["//visibility:public"],
    deps = ["//vendor/golang.org/x/xerrors/internal:go_default_library"],
)
