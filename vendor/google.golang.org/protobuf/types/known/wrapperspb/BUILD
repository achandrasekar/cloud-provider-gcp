load("@io_bazel_rules_go//go:def.bzl", "go_library")

go_library(
    name = "go_default_library",
    srcs = ["wrappers.pb.go"],
    importmap = "k8s.io/cloud-provider-gcp/vendor/google.golang.org/protobuf/types/known/wrapperspb",
    importpath = "google.golang.org/protobuf/types/known/wrapperspb",
    visibility = ["//visibility:public"],
    deps = [
        "//vendor/google.golang.org/protobuf/reflect/protoreflect:go_default_library",
        "//vendor/google.golang.org/protobuf/runtime/protoimpl:go_default_library",
    ],
)
