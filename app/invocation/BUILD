load("@npm_bazel_typescript//:index.bzl", "ts_library")

package(default_visibility = ["//visibility:public"])

exports_files(glob(["*.css"]))

ts_library(
    name = "invocation",
    srcs = glob(["**/*.tsx"]),
    deps = [
        "//app/auth",
        "//app/capabilities",
        "//app/components/button",
        "//app/components/dialog",
        "//app/components/input",
        "//app/components/modal",
        "//app/components/select",
        "//app/docs",
        "//app/favicon",
        "//app/flame_chart",
        "//app/format",
        "//app/router",
        "//app/service",
        "//app/target",
        "//app/terminal",
        "//proto:build_event_stream_ts_proto",
        "//proto:cache_ts_proto",
        "//proto:command_line_ts_proto",
        "//proto:invocation_ts_proto",
        "//proto:user_ts_proto",
        "@npm//@types/long",
        "@npm//@types/moment",
        "@npm//@types/pako",
        "@npm//@types/react",
        "@npm//@types/recharts",
        "@npm//long",
        "@npm//moment",
        "@npm//pako",
        "@npm//protobufjs",
        "@npm//react",
        "@npm//recharts",
        "@npm//tslib",
    ],
)
