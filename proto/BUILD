load("@org_pubref_rules_protobuf//cpp:rules.bzl", "cc_proto_library")

cc_proto_library(
  name = "base_cc_pb",
  protos = ["base.proto"],
)

cc_proto_library(
  name = "test_cc_pb",
  protos = ["test.proto"],
  proto_deps = [":base_cc_pb"],
)
