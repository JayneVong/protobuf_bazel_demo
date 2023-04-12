load("@bazel_tools//tools/build_defs/repo:http.bzl", "http_archive")

http_archive(
    name = "com_google_googletest",
    sha256 = "730215d76eace9dd49bf74ce044e8daa065d175f1ac891cc1d6bb184ef94e565",
    strip_prefix = "googletest-f53219cdcb7b084ef57414efea92ee5b71989558",
    urls = [
        "https://github.com/google/googletest/archive/f53219cdcb7b084ef57414efea92ee5b71989558.tar.gz" # 2023-03-16
    ],
)

load("@com_google_googletest//:googletest_deps.bzl", "googletest_deps")

googletest_deps()

http_archive(
    name = "com_google_protobuf",
    strip_prefix = "protobuf-22.2",
    #urls = ["https://github.com/protocolbuffers/protobuf/archive/v3.11.3.tar.gz"],
    urls = ["https://github.com/protocolbuffers/protobuf/releases/download/v22.2/protobuf-22.2.tar.gz"]
)

load("@com_google_protobuf//:protobuf_deps.bzl", "protobuf_deps")
protobuf_deps()

# # rules_cc defines rules for generating C++ code from Protocol Buffers. 
# http_archive( 
#     name = "rules_cc", 
#     sha256 = "35f2fb4ea0b3e61ad64a369de284e4fbbdcdba71836a5555abb5e194cf119509", 
#     strip_prefix = "rules_cc-624b5d59dfb45672d4239422fa1e3de1822ee110", 
#     urls = [ 
#         "https://mirror.bazel.build/github.com/bazelbuild/rules_cc/archive/624b5d59dfb45672d4239422fa1e3de1822ee110.tar.gz", 
#         "https://github.com/bazelbuild/rules_cc/archive/624b5d59dfb45672d4239422fa1e3de1822ee110.tar.gz", 
#     ], 
# ) 

# # rules_java defines rules for generating Java code from Protocol Buffers. 
# http_archive( 
#     name = "rules_java", 
#     sha256 = "ccf00372878d141f7d5568cedc4c42ad4811ba367ea3e26bc7c43445bbc52895", 
#     strip_prefix = "rules_java-d7bf804c8731edd232cb061cb2a9fe003a85d8ee", 
#     urls = [ 
#         "https://mirror.bazel.build/github.com/bazelbuild/rules_java/archive/d7bf804c8731edd232cb061cb2a9fe003a85d8ee.tar.gz", 
#         "https://github.com/bazelbuild/rules_java/archive/d7bf804c8731edd232cb061cb2a9fe003a85d8ee.tar.gz", 
#     ], 
# ) 

# # rules_proto defines abstract rules for building Protocol Buffers. 
# http_archive( 
#     name = "rules_proto", 
#     sha256 = "2490dca4f249b8a9a3ab07bd1ba6eca085aaf8e45a734af92aad0c42d9dc7aaf", 
#     strip_prefix = "rules_proto-218ffa7dfa5408492dc86c01ee637614f8695c45", 
#     urls = [ 
#         "https://mirror.bazel.build/github.com/bazelbuild/rules_proto/archive/218ffa7dfa5408492dc86c01ee637614f8695c45.tar.gz", 
#         "https://github.com/bazelbuild/rules_proto/archive/218ffa7dfa5408492dc86c01ee637614f8695c45.tar.gz", 
#     ], 
# ) 

# load("@rules_cc//cc:repositories.bzl", "rules_cc_dependencies") 
# rules_cc_dependencies() 

# load("@rules_java//java:repositories.bzl", "rules_java_dependencies", "rules_java_toolchains") 
# rules_java_dependencies() 
# rules_java_toolchains() 

# load("@rules_proto//proto:repositories.bzl", "rules_proto_dependencies", "rules_proto_toolchains") 
# rules_proto_dependencies() 
# rules_proto_toolchains() 