load("@io_bazel_rules_go//go:def.bzl", "go_library")

go_library(
    name = "go_default_library",
    srcs = [
        "crd.go",
        "doc.go",
        "package.go",
        "register.go",
        "topology.go",
        "validation.go",
        "zz_generated.markerhelp.go",
    ],
    importmap = "k8s.io/cloud-provider-gcp/vendor/sigs.k8s.io/controller-tools/pkg/crd/markers",
    importpath = "sigs.k8s.io/controller-tools/pkg/crd/markers",
    visibility = ["//visibility:public"],
    deps = [
        "//vendor/k8s.io/apiextensions-apiserver/pkg/apis/apiextensions/v1:go_default_library",
        "//vendor/sigs.k8s.io/controller-tools/pkg/markers:go_default_library",
    ],
)
