# Description: TensorFlow Serving session_bundle example.

package(
    default_visibility = ["//tensorflow/contrib/session_bundle:__subpackages__"],
    licenses = ["notice"],  # Apache 2.0
)

exports_files(["LICENSE"])

# vardef("PYTHON_BIN_PATH", "/usr/bin/python")

py_binary(
    name = "export_half_plus_two",
    srcs = [
        "export_half_plus_two.py",
    ],
    python_version = "PY2",
    srcs_version = "PY2AND3",
    deps = [
        "//tensorflow:tensorflow_py",
        "//tensorflow/contrib/session_bundle:exporter",
    ],
)
