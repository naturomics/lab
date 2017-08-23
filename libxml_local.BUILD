# Description:
# 	Build rule for libxml2.
# 	This is not an official BUILD file.

cc_library(
		name = "libxml",
		srcs = glob(["lib64/libxml*.so"]),
		hdrs = glob(["include/libxml2/libxml/*.h"]),
		includes = ["include/libxml2/", "include/libxml2/libxml"],
		copts = ["-Iinclude/libxml2/libxml"],
		visibility = ["//visibility:public"],
)
