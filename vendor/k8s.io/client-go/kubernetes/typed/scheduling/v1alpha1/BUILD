load("@io_bazel_rules_go//go:def.bzl", "go_library")

go_library(
    name = "go_default_library",
    srcs = [
        "doc.go",
        "generated_expansion.go",
        "priorityclass.go",
        "scheduling_client.go",
    ],
    importmap = "k8s.io/cloud-provider-gcp/vendor/k8s.io/client-go/kubernetes/typed/scheduling/v1alpha1",
    importpath = "k8s.io/client-go/kubernetes/typed/scheduling/v1alpha1",
    visibility = ["//visibility:public"],
    deps = [
        "//vendor/k8s.io/api/scheduling/v1alpha1:go_default_library",
        "//vendor/k8s.io/apimachinery/pkg/apis/meta/v1:go_default_library",
        "//vendor/k8s.io/apimachinery/pkg/types:go_default_library",
        "//vendor/k8s.io/apimachinery/pkg/watch:go_default_library",
        "//vendor/k8s.io/client-go/applyconfigurations/scheduling/v1alpha1:go_default_library",
        "//vendor/k8s.io/client-go/kubernetes/scheme:go_default_library",
        "//vendor/k8s.io/client-go/rest:go_default_library",
    ],
)
