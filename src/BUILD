cc_binary(
    name = "main",
    srcs = ["main.cpp", "glad.h", "glad.c"],
    linkopts =[
      "-ldl",
      "-lpthread",
     # "-lopengl32",
      "-lGL",
    ],
    deps = [
      "@glfw//:glfw",
    ],
)