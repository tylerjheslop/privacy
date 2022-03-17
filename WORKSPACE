workspace(name = "org_tensorflow_privacy")

load("@bazel_tools//tools/build_defs/repo:git.bzl", "git_repository")

git_repository(
    name = "bazel_skylib",
    remote = "https://github.com/bazelbuild/bazel-skylib.git",
    tag = "1.0.3",
)

git_repository(
    name = "rules_python",
    remote = "https://github.com/bazelbuild/rules_python.git",
    tag = "0.5.0",
)

git_repository(
  name = "differential-privacy",
  remote = "https://github.com/google/differential-privacy.git",
  commit = "8536a3af6b147b1cce6f884826bfd5f2009ae50f",
)
