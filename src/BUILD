cc_binary(
    name = "main",
    srcs = ["main.cpp"],
    linkopts =[
      "-ldl",
      "-lpthread",
      "-lGL",
    ],
    deps = [
      "@glfw//:glfw",
      "//glad:glad"
    ],
)