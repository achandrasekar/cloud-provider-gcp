load("@io_bazel_rules_go//go:def.bzl", "go_library")

go_library(
    name = "go_default_library",
    srcs = [
        "event.go",
        "eventseries.go",
    ],
    importmap = "k8s.io/cloud-provider-gcp/vendor/k8s.io/client-go/applyconfigurations/events/v1beta1",
    importpath = "k8s.io/client-go/applyconfigurations/events/v1beta1",
    visibility = ["//visibility:public"],
    deps = [
        "//vendor/k8s.io/api/events/v1beta1:go_default_library",
        "//vendor/k8s.io/apimachinery/pkg/apis/meta/v1:go_default_library",
        "//vendor/k8s.io/apimachinery/pkg/types:go_default_library",
        "//vendor/k8s.io/apimachinery/pkg/util/managedfields:go_default_library",
        "//vendor/k8s.io/client-go/applyconfigurations/core/v1:go_default_library",
        "//vendor/k8s.io/client-go/applyconfigurations/internal:go_default_library",
        "//vendor/k8s.io/client-go/applyconfigurations/meta/v1:go_default_library",
    ],
)
