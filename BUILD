load("@io_bazel_rules_scala//scala:scala.bzl", "scala_library", "scala_binary", "scala_test")


scala_library(
    name = "genericScalaPlugin",
    srcs = glob(["src/main/java/**/*.java"]),
    print_compile_time = True,
    deps = [ 
        "@com_google_inject_guice//jar", 
        "@com_google_gerrit_gerrit_plugin_api//jar"
    ],
)

