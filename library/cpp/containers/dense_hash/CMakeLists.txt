
# This file was gererated by the build system used internally in the Yandex monorepo.
# Only simple modifications are allowed (adding source-files to targets, adding simple properties
# like target_include_directories). These modifications will be ported to original
# ya.make files by maintainers. Any complex modifications which can't be ported back to the
# original buildsystem will not be accepted.



add_library(cpp-containers-dense_hash)
target_link_libraries(cpp-containers-dense_hash PUBLIC
  contrib-libs-cxxsupp
  yutil
)
target_sources(cpp-containers-dense_hash PRIVATE
  ${CMAKE_SOURCE_DIR}/library/cpp/containers/dense_hash/dense_hash.cpp
)
