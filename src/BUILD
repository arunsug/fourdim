cc_binary(
    name = "main",
    srcs = ["main.cpp", "GLAD/glad.h", "GLAD/glad.c", "KHR/khrplatform.h"],
    linkopts =[
      "-ldl",
      "-lpthread",
      "-lGL",
    ],
    deps = [
      "@glfw//:glfw",
    ],
)