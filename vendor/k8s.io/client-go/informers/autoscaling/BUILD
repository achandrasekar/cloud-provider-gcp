load("@io_bazel_rules_go//go:def.bzl", "go_library")

go_library(
    name = "go_default_library",
    srcs = ["interface.go"],
    importmap = "k8s.io/cloud-provider-gcp/vendor/k8s.io/client-go/informers/autoscaling",
    importpath = "k8s.io/client-go/informers/autoscaling",
    visibility = ["//visibility:public"],
    deps = [
        "//vendor/k8s.io/client-go/informers/autoscaling/v1:go_default_library",
        "//vendor/k8s.io/client-go/informers/autoscaling/v2:go_default_library",
        "//vendor/k8s.io/client-go/informers/autoscaling/v2beta1:go_default_library",
        "//vendor/k8s.io/client-go/informers/autoscaling/v2beta2:go_default_library",
        "//vendor/k8s.io/client-go/informers/internalinterfaces:go_default_library",
    ],
)
