load("@io_bazel_rules_go//go:def.bzl", "go_library")

go_library(
    name = "go_default_library",
    srcs = [
        "decode.go",
        "encode.go",
        "json.go",
    ],
    importmap = "k8s.io/cloud-provider-gcp/vendor/github.com/golang/protobuf/jsonpb",
    importpath = "github.com/golang/protobuf/jsonpb",
    visibility = ["//visibility:public"],
    deps = [
        "//vendor/github.com/golang/protobuf/proto:go_default_library",
        "//vendor/google.golang.org/protobuf/encoding/protojson:go_default_library",
        "//vendor/google.golang.org/protobuf/proto:go_default_library",
        "//vendor/google.golang.org/protobuf/reflect/protoreflect:go_default_library",
        "//vendor/google.golang.org/protobuf/reflect/protoregistry:go_default_library",
        "//vendor/google.golang.org/protobuf/runtime/protoimpl:go_default_library",
    ],
)
