git_repository(
    name = "io_bazel_rules_go",
    remote = "https://github.com/bazelbuild/rules_go.git",
    tag = "0.5.3",
)

load("@io_bazel_rules_go//go:def.bzl", "go_repositories")
load("@io_bazel_rules_go//proto:go_proto_library.bzl", "go_proto_repositories")

go_repositories()

go_proto_repositories()
