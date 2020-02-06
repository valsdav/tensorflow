licenses(["notice"])  # BSD

filegroup(
    name = "LICENCE",
    visibility = ["//visibility:public"],
)

cc_library(
    name = "pcre",
    linkopts = ["-Lexternal/pcre/lib -lpcre"],
    includes = ["include"],
    visibility = ["//visibility:public"],
)
