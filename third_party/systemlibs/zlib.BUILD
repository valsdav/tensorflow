licenses(["notice"])  # BSD/MIT-like license (for zlib)

filegroup(
    name = "zlib.h",
    visibility = ["//visibility:public"],
)

cc_library(
    name = "zlib",
    linkopts = ["-Lexternal/zlib_archive/lib -lz"],
    includes = ["include"],
    visibility = ["//visibility:public"],
)
