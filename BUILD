load("@bazel_gazelle//:def.bzl", "DEFAULT_LANGUAGES", "gazelle_binary", "gazelle")

gazelle_binary(
    name = "gazelle_sass",
    languages = ["@io_bazel_rules_sass//gazelle:go_default_library"],
    visibility = ["//visibility:public"],
)

# gazelle:prefix github.com/mgechev/sass-example
gazelle(
    name = "gazelle",
    gazelle = "gazelle_sass",
)
