# Prebuilt binaries gRPC C++ for Windows

##### Current stable build of gRPC v1.20.0 ( https://grpc.io/release ) | 06-26-19

Build instructions from here: https://github.com/grpc/grpc/blob/master/BUILDING.md

HelloWorld-Example included. Tested with VS2017 Enterprise and msvc141 (Win 10, SDK 10.0.17763.0)

#### Information about Buildsystem and Tools

| Operating System | SDK Version   |
|------------------|---------------|
| Windows 10 (x64) |  10.0.17763.0 |

| Build Tool       | Version        |
|------------------|----------------|
| yasm             | 1.20           |
| ninja            | 1.9.0.20190208 |
| cmake            | 3.14.4         |
| golang           | 1.12.6         |
| activeperl       | 5.24.3.2404    |
| MSVC 140         | 19.00.24245.0  |
| MSVC 141         | 19.16.27027.1  |
| MSVC 142         | 19.21.27702.2  |

#### gRPC c++ Third Party Components

| Third Party Component | Version      | Link                                     |
|-----------------------|--------------|------------------------------------------|
| zlib                  | ---          | https://github.com/madler/zlib           |
| protobuf              | 3.0.x        | https://github.com/google/protobuf.git   |
| gflags                | ---          | https://github.com/gflags/gflags.git     |
| googletest            | ---          | https://github.com/google/googletest.git |
| boringssl             | ---          | https://github.com/google/boringssl.git  |
| benchmark             | ---          | https://github.com/google/benchmark.git  |
| boringssl-with-bazel  | ---          | https://github.com/google/boringssl.git  |
| cares                 | cares-1_12_0 | https://github.com/c-ares/c-ares.git     |
| bloaty                | ---          | https://github.com/google/bloaty.git     |
| abseil-cpp            | ---          | https://github.com/abseil/abseil-cpp.git |
| libcxxabi             | release_60   | https://github.com/llvm-mirror/libcxxabi.git |
| libcxx                | release_60   | https://github.com/llvm-mirror/libcxx.git  |
| data-plane-aip        | ---          | https://github.com/envoyproxy/data-plane-api.git |
| googleapis            | ---          | https://github.com/googleapis/googleapis.git |
| protoc-gen-validate   | ---          | https://github.com/lyft/protoc-gen-validate.git |
| upb                   | ---          | https://github.com/google/upb.git        |




