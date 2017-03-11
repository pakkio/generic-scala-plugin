git_repository(
    name = "io_bazel_rules_scala",
    remote = "https://github.com/bazelbuild/rules_scala.git",
    commit = "73743b830ae98d13a946b25ad60cad5fee58e6d3", # update this as needed
)

maven_jar(
    name = "com_google_inject_guice",
    artifact = "com.google.inject:guice:3.0",
)
maven_jar(
	name = "com_google_gerrit_gerrit_plugin_api",
	artifact = "com.google.gerrit:gerrit-plugin-api:2.13.6"
)

load("@io_bazel_rules_scala//scala:scala.bzl", "scala_repositories")
scala_repositories()