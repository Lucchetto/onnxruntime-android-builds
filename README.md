# ONNX Runtime builds for Android

[![Latest Release](https://img.shields.io/github/v/release/Lucchetto/onnxruntime-android-builds)](https://github.com/Lucchetto/onnxruntime-android-builds/releases/latest)
[![Create ONNX Runtime release](https://github.com/Lucchetto/onnxruntime-android-builds/actions/workflows/create-release.yml/badge.svg)](https://github.com/Lucchetto/onnxruntime-android-builds/actions/workflows/create-release.yml)

This repository provides pre-built binaries of [ONNX Runtime](https://github.com/microsoft/onnxruntime) for Android. These builds only include the default CPU Execution Provider.

# Supported ABIs

The following Android ABIs are built:

- `armeabi-v7a`
- `x86_64`

# Build configuration

The binaries are built with the `RelWithDebInfo` configuration, which provides optimised code with debug symbols included.

# Releases

The current release and past releases of the binaries can be found here: https://github.com/Lucchetto/onnxruntime-android-builds/releases.

Each release provides a single archive named `onnxruntime-android-<version>.zip` containing the shared library for every supported ABI:

```
onnxruntime-android-<version>.zip
├── armeabi-v7a/libonnxruntime.so
└── x86_64/libonnxruntime.so
```
