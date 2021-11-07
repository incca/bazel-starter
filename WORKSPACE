load("@bazel_tools//tools/build_defs/repo:http.bzl", "http_archive")

http_archive(
    name = "build_bazel_rules_nodejs",
    sha256 = "3720e99520c0bd31d23bf04cf365db934c5fa77badf68a8aaea523bbd442851a",
    urls = ["https://github.com/bazelbuild/rules_nodejs/releases/download/4.4.3/rules_nodejs-4.4.3.tar.gz"],
)

load("@build_bazel_rules_nodejs//:index.bzl", "node_repositories")

node_repositories(
    node_version = "16.13.0",
)
