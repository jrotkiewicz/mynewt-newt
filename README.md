<!--
#
# Licensed to the Apache Software Foundation (ASF) under one
# or more contributor license agreements.  See the NOTICE file
# distributed with this work for additional information
# regarding copyright ownership.  The ASF licenses this file
# to you under the Apache License, Version 2.0 (the
# "License"); you may not use this file except in compliance
# with the License.  You may obtain a copy of the License at
#
# http://www.apache.org/licenses/LICENSE-2.0
#
# Unless required by applicable law or agreed to in writing,
# software distributed under the License is distributed on an
# "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY
#  KIND, either express or implied.  See the License for the
# specific language governing permissions and limitations
# under the License.
#
-->

# Newt

Apache Newt is a build and package management tool for embedded projects. Newt
makes it easy to create reusable components, and provides a framework for
building them for multiple different architectures.  For more information on
Apache Newt and related tools, please go to: http://mynewt.apache.org/

Apache Newt and related tools are written in the Go programming language.
After acquiring the Go build system (https://golang.org/), Newt can be built
using the following procedure (from the base of the newt repository):
    $ cd newt
    $ go get
    $ go install

This procedure will install the Newt binary into $GOPATH/bin.

For more detailed instructions on getting Newt up and running, see the Apache
Mynewt Getting Started page at:
http://mynewt.apache.org/os/get_started/project1/

Note: Apache Newt depends on the yaml.v2 Go package (https://gopkg.in/yaml.v2).
This package is licensed under the LGPLv3, which is incompatible with the
Apache 2.0 license.  This incompatibility will be resolved in a future beta
release.