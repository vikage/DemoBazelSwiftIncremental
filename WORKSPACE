load("@bazel_tools//tools/build_defs/repo:http.bzl", "http_archive")

http_archive(
    name = "build_bazel_rules_swift",
    sha256 = "5bb49e7a1764f3f227677c572d6487b5bfeb2613eaaae2a82b240d9b836a0b4e",
    url = "https://github.com/bazelbuild/rules_swift/releases/download/2.3.1/rules_swift.2.3.1.tar.gz",
)

load(
    "@build_bazel_rules_swift//swift:repositories.bzl",
    "swift_rules_dependencies",
)

swift_rules_dependencies()

load(
    "@build_bazel_rules_swift//swift:extras.bzl",
    "swift_rules_extra_dependencies",
)

swift_rules_extra_dependencies()