load("@io_bazel_rules_scala//scala:scala.bzl", "scala_library", "scala_binary", "scala_test")


scala_library(
    name = "generic-scala-plugin",
    srcs = glob(["src/main/scala/**/*.scala"]),
    print_compile_time = True,
    deps = [ 
        "@com_google_inject_guice//jar", 
        "@com_google_gerrit_gerrit_plugin_api//jar"
    ],
)

