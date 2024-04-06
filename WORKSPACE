load("@bazel_tools//tools/build_defs/repo:http.bzl", "http_archive")

http_archive(
    name = "oss_eclipse_iceoryx",
    sha256 = "cfc426a02a44b0c092e12482d2f40c150ce04b48f80f066592999ca3306f05fe",
    strip_prefix = "iceoryx-515bcf6be9e2a7f5fa38c90d095b1078889251c9",
    urls = [
        "https://github.com/eclipse-iceoryx/iceoryx/archive/515bcf6be9e2a7f5fa38c90d095b1078889251c9.zip",
    ]
)

load("@oss_eclipse_iceoryx//bazel:load_repositories.bzl", "load_repositories")
load_repositories()
load("@oss_eclipse_iceoryx//bazel:setup_repositories.bzl", "setup_repositories")
setup_repositories()
