load("@io_bazel_rules_go//go:def.bzl", "go_library")

go_library(
    name = "go_default_library",
    srcs = [
        "clientset.go",
        "doc.go",
    ],
    importpath = "k8s.io/cloud-provider-gcp/crd/client/gcpfirewall/clientset/versioned",
    visibility = ["//visibility:public"],
    deps = [
        "//crd/client/gcpfirewall/clientset/versioned/typed/gcpfirewall/v1alpha1:go_default_library",
        "//vendor/k8s.io/client-go/discovery:go_default_library",
        "//vendor/k8s.io/client-go/rest:go_default_library",
        "//vendor/k8s.io/client-go/util/flowcontrol:go_default_library",
    ],
)
