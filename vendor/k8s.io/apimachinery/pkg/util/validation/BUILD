package(default_visibility = ["//visibility:public"])

load("@io_bazel_rules_go//go:def.bzl", "go_library")

go_library(
    name = "go_default_library",
    srcs = ["validation.go"],
    importmap = "https:/github.com/GoogleCloudPlatform/k8s-cloudkms-plugin/vendor/k8s.io/apimachinery/pkg/util/validation",
    importpath = "k8s.io/apimachinery/pkg/util/validation",
    deps = ["//vendor/k8s.io/apimachinery/pkg/util/validation/field:go_default_library"],
)
