# Graal Development Kit for Micronaut&reg; plugin

This IntelliJ IDEA plugin provides a [Graal Development Kit for Micronaut&reg; (GDK)](https://graal.cloud/gdk/) project wizard which helps you generate GDK applications.

GDK is a curated set of open source Micronaut® framework modules designed from the ground up to be compiled ahead-of-time with GraalVM Native Image resulting in native executables ideal for microservices.

IntelliJ IDEA Ultimate Micronaut support is automatically enabled for GDK projects. 
Graal Development Kit for Micronaut was formerly Graal Cloud Native.

## Build plugin from sources

To build `.zip` file that corresponds to IntelliJ plugin format, take the following steps.

Optionally:
- Build [gdk project](https://graal.cloud/gdk/) separately and publish it to local Maven repo with gradle `./gradlew publishToMavenLocal`

Build plugin with gradle `./gradlew build`

Plugin should be located in `/build/distributions`

## Installation

Plugin can be installed through IntelliJ graphical interface:
- Install using IntelliJ Settings panel | Plugins from Marketplace

Or if installing from local zip file:
- Open settings panel and navigate to Plugins section on the left
- Select `install plugin from disk` option and navigate to the `.zip` file
- Restart the IDE

## Contributing

This project welcomes contributions from the community. Before submitting a pull request, please [review our contribution guide](./CONTRIBUTING.md)

## Security

Please consult the [security guide](./SECURITY.md) for our responsible security vulnerability disclosure process


## License

Copyright (c) 2019, 2024, Oracle and/or its affiliates. All rights reserved.

Released under the [Apache License version 2.0](LICENSE.txt).

---
Micronaut® is a registered trademark of Object Computing, Inc. Use is for referential purposes and does not imply any endorsement or affiliation with any third-party product. Unauthorized use is strictly prohibited.
