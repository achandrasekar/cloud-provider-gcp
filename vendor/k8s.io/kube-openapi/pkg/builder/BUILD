load("@io_bazel_rules_go//go:def.bzl", "go_library")

go_library(
    name = "go_default_library",
    srcs = [
        "doc.go",
        "openapi.go",
        "util.go",
    ],
    importmap = "k8s.io/cloud-provider-gcp/vendor/k8s.io/kube-openapi/pkg/builder",
    importpath = "k8s.io/kube-openapi/pkg/builder",
    visibility = ["//visibility:public"],
    deps = [
        "//vendor/github.com/emicklei/go-restful:go_default_library",
        "//vendor/k8s.io/kube-openapi/pkg/common:go_default_library",
        "//vendor/k8s.io/kube-openapi/pkg/util:go_default_library",
        "//vendor/k8s.io/kube-openapi/pkg/validation/spec:go_default_library",
    ],
)
