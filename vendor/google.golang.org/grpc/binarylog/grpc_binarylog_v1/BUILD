load("@io_bazel_rules_go//go:def.bzl", "go_library")

go_library(
    name = "go_default_library",
    srcs = ["binarylog.pb.go"],
    importmap = "k8s.io/cloud-provider-gcp/vendor/google.golang.org/grpc/binarylog/grpc_binarylog_v1",
    importpath = "google.golang.org/grpc/binarylog/grpc_binarylog_v1",
    visibility = ["//visibility:public"],
    deps = [
        "//vendor/github.com/golang/protobuf/proto:go_default_library",
        "//vendor/google.golang.org/protobuf/reflect/protoreflect:go_default_library",
        "//vendor/google.golang.org/protobuf/runtime/protoimpl:go_default_library",
        "//vendor/google.golang.org/protobuf/types/known/durationpb:go_default_library",
        "//vendor/google.golang.org/protobuf/types/known/timestamppb:go_default_library",
    ],
)
