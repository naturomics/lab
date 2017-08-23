# Description:
#   Build rule for zlib.


cc_library(
		name = "zlib",
		srcs = glob(["lib64/*zip.so"]),
		hdrs = glob(["include/*.h", "include/minizip/*.h",]),
		includes = ["lib64", "lib32", "include", "include/minizip"],
		copts = ["-Ilib64", "-Iinclude", "-Iinclude/minizip"],
		visibility = ["//visibility:public"],
)
