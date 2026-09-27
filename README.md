# fx.controls

[English](README.md) | [简体中文](README.zh-CN.md)

Module identity and dependencies: [module.norm](fx/controls/module.norm). Package toolchain: [workflow](.github/workflows/package.yml).

Build: `norm package fx/controls --output build/repository`.

Validated on Windows x64 with JVM execution and Native application startup. JavaFX artifacts are resolved from Maven Central; Norm packages are distributed through GitHub Releases. [Native reachability metadata](fx/controls/resources/META-INF/native-image/org.openjfx/javafx-controls/reachability-metadata.json) follows [GraalVM's format](https://www.graalvm.org/jdk25/reference-manual/native-image/metadata/).

[Sample ownership](samples/README.md).
