load("//tensorboard/defs:defs.bzl", "tf_ts_library")

package(default_visibility = ["//tensorboard:internal"])

licenses(["notice"])

tf_ts_library(
    name = "tf_audio_dashboard",
    srcs = [
        "tf-audio-dashboard.ts",
        "tf-audio-loader.ts",
    ],
    strict_checks = False,
    deps = [
        "//tensorboard/components_polymer3/polymer:irons_and_papers",
        "//tensorboard/components_polymer3/polymer:legacy_element_mixin",
        "//tensorboard/components_polymer3/tf_backend",
        "//tensorboard/components_polymer3/tf_card_heading",
        "//tensorboard/components_polymer3/tf_categorization_utils",
        "//tensorboard/components_polymer3/tf_color_scale",
        "//tensorboard/components_polymer3/tf_dashboard_common",
        "//tensorboard/components_polymer3/tf_markdown_view",
        "//tensorboard/components_polymer3/tf_paginated_view",
        "//tensorboard/components_polymer3/tf_runs_selector",
        "@npm//@polymer/decorators",
        "@npm//@polymer/polymer",
        "@npm//@types/d3",
        "@npm//@types/lodash",
        "@npm//d3",
        "@npm//lodash",
    ],
)
