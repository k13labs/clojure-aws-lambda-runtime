[![Build Status](https://github.com/k13labs/clojure-aws-lambda-runtime/actions/workflows/clojure.yml/badge.svg)](https://github.com/k13labs/clojure-aws-lambda-runtime/actions/workflows/clojure.yml)

# _About_

clojure-aws-lambda-runtime is a [custom runtime](https://docs.aws.amazon.com/lambda/latest/dg/runtimes-custom.html)
for running AWS Lambda functions written in Clojure, with compatibility to compile them into native programs using GraalVM.

# _Usage_

Here's a simple example.

```clj
(ns user
  (:require [clojure-aws-lambda-runtime.core :refer :all])

;;; => returns `[[1 1 2 4] [1 3 4 8] [3 1 4 8] [3 3 6 12]]` evaluated fully async and takes slightly over 50ms total time.
```

See the existing tests for more examples.

# _Building_

clojure-aws-lambda-runtime is built, tested, and deployed using [Clojure Tools Deps](https://clojure.org/guides/deps_and_cli).

GNU Make is used to simplify invocation of some commands.

# _Availability_

clojure-aws-lambda-runtime releases for this project are on [Clojars](https://clojars.org/). Simply add the following to your project:

[![Clojars Project](http://clojars.org/com.github.k13labs/clojure-aws-lambda-runtime/latest-version.svg)](http://clojars.org/com.github.k13labs/clojure-aws-lambda-runtime)

# _Communication_

- For any other questions or issues about clojure-aws-lambda-runtime free to browse or open a [Github Issue](https://github.com/k13labs/clojure-aws-lambda-runtime/issues).

# Contributing

See [CONTRIBUTING.md](CONTRIBUTING.md)

# YourKit

[![YourKit](https://www.yourkit.com/images/yklogo.png)](https://www.yourkit.com/)

YourKit supports open source projects with innovative and intelligent tools
for monitoring and profiling Java and .NET applications.
YourKit is the creator of [YourKit Java Profiler](https://www.yourkit.com/java/profiler/),
[YourKit .NET Profiler](https://www.yourkit.com/dotnet-profiler/),
and [YourKit YouMonitor](https://www.yourkit.com/youmonitor/).

# LICENSE

Copyright 2024 Jose Gomez

Licensed under the Apache License, Version 2.0 (the "License"); you may not use this file except in compliance with the License. You may obtain a copy of the License at

&nbsp;&nbsp;&nbsp;&nbsp;http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software distributed under the License is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the License for the specific language governing permissions and limitations under the License.
