load("@io_bazel_rules_go//go:def.bzl", "go_library")

go_library(
    name = "go_default_library",
    srcs = ["webhook.go"],
    importmap = "k8s.io/cloud-provider-gcp/vendor/k8s.io/apiserver/plugin/pkg/audit/webhook",
    importpath = "k8s.io/apiserver/plugin/pkg/audit/webhook",
    visibility = ["//visibility:public"],
    deps = [
        "//vendor/k8s.io/apimachinery/pkg/runtime/schema:go_default_library",
        "//vendor/k8s.io/apimachinery/pkg/util/net:go_default_library",
        "//vendor/k8s.io/apimachinery/pkg/util/wait:go_default_library",
        "//vendor/k8s.io/apiserver/pkg/apis/audit:go_default_library",
        "//vendor/k8s.io/apiserver/pkg/apis/audit/install:go_default_library",
        "//vendor/k8s.io/apiserver/pkg/audit:go_default_library",
        "//vendor/k8s.io/apiserver/pkg/util/webhook:go_default_library",
        "//vendor/k8s.io/client-go/rest:go_default_library",
        "//vendor/k8s.io/utils/trace:go_default_library",
    ],
)
