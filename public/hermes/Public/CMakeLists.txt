# Copyright (c) Meta Platforms, Inc. and affiliates.
#
# This source code is licensed under the MIT license found in the
# LICENSE file in the root directory of this source tree.

install(DIRECTORY "${PROJECT_SOURCE_DIR}/public/hermes/Public" DESTINATION include/hermes
  FILES_MATCHING PATTERN "*.h")
