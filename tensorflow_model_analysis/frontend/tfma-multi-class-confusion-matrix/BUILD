licenses(["notice"])  # Apache 2.0

load("@io_bazel_rules_closure//closure:defs.bzl", "web_library")

package(
    default_visibility = ["//tensorflow_model_analysis:__subpackages__"],
)

web_library(
    name = "lib",
    srcs = [
        "tfma-multi-class-confusion-matrix.html",
        "tfma-multi-class-confusion-matrix.js",
    ],
    path = "/tfma-multi-class-confusion-matrix",
    deps = [
        "@org_polymer",
    ],
)
