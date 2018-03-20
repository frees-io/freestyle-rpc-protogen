[comment]: # (Start Badges)

[![Build Status](https://travis-ci.org/frees-io/sbt-freestyle-protogen.svg?branch=master)](https://travis-ci.org/frees-io/sbt-freestyle-protogen) [![codecov.io](http://codecov.io/github/frees-io/sbt-freestyle-protogen/coverage.svg?branch=master)](http://codecov.io/github/frees-io/sbt-freestyle-protogen?branch=master) [![Latest version](https://img.shields.io/badge/sbt--freestyle--protogen-0.0.14-green.svg)](https://index.scala-lang.org/frees-io/sbt-freestyle-protogen) [![License](https://img.shields.io/badge/license-Apache%202-blue.svg)](https://raw.githubusercontent.com/frees-io/sbt-freestyle-protogen/master/LICENSE) [![Join the chat at https://gitter.im/47deg/freestyle](https://badges.gitter.im/47deg/freestyle.svg)](https://gitter.im/47deg/freestyle?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge) [![GitHub Issues](https://img.shields.io/github/issues/frees-io/sbt-freestyle-protogen.svg)](https://github.com/frees-io/sbt-freestyle-protogen/issues)

[comment]: # (End Badges)

# sbt-frees-protogen

:warning: **Note: this project is deprecated and has been integrated into the [frees-rpc](https://github.com/frees-io/freestyle-rpc) codebase as `sbt-frees-rpc-idlgen` starting with version 0.12.0.**

Sbt plugin to generate .proto files from freestyle-rpc service definitions.

It depends on [frees-rpc](https://github.com/frees-io/freestyle-rpc).

## Legacy Installation

Add the following line to `project/plugins.sbt`:


[comment]: # (Start Replace)

```scala
addSbtPlugin("io.frees" % "sbt-frees-protogen" % "0.0.14")
```

[comment]: # (End Replace)

## Legacy Usage

Running
```scala
sbt protoGen
```
will generate `.proto` files from `src/main/scala` into `src/main/proto/`. These directories can be changed using the `protoGenSourceDir` and `protoGenTargetDir` settings.

[comment]: # (Start Copyright)
# Copyright

Freestyle is designed and developed by 47 Degrees

Copyright (C) 2017 47 Degrees. <http://47deg.com>

[comment]: # (End Copyright)
