load("@io_bazel_rules_go//go:def.bzl", "go_library")

go_library(
    name = "go_default_library",
    srcs = ["memcache.go"],
    importmap = "k8s.io/cloud-provider-gcp/vendor/k8s.io/client-go/discovery/cached/memory",
    importpath = "k8s.io/client-go/discovery/cached/memory",
    visibility = ["//visibility:public"],
    deps = [
        "//vendor/github.com/googleapis/gnostic/openapiv2:go_default_library",
        "//vendor/k8s.io/apimachinery/pkg/api/errors:go_default_library",
        "//vendor/k8s.io/apimachinery/pkg/apis/meta/v1:go_default_library",
        "//vendor/k8s.io/apimachinery/pkg/util/runtime:go_default_library",
        "//vendor/k8s.io/apimachinery/pkg/version:go_default_library",
        "//vendor/k8s.io/client-go/discovery:go_default_library",
        "//vendor/k8s.io/client-go/rest:go_default_library",
    ],
)
