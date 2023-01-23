workspace(name = "com_github_storypku_rules_folly")

load("@bazel_tools//tools/build_defs/repo:http.bzl", "http_archive")
load("//bazel:folly_deps.bzl", "folly_deps")

folly_deps(with_gflags = 1)

load("@com_github_nelhage_rules_boost//:boost/boost.bzl", "boost_deps")

boost_deps()

http_archive(
    name = "com_google_googletest",
    sha256 = "ad7fdba11ea011c1d925b3289cf4af2c66a352e18d4c7264392fead75e919363",
    strip_prefix = "googletest-release-1.13.0",
    urls = [
        "https://github.com/google/googletest/archive/release-1.13.0.tar.gz",
    ],
)
