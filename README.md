brackish
===

[![Maven Central](https://img.shields.io/maven-central/v/com.io7m.brackish/com.io7m.brackish.svg?style=flat-square)](http://search.maven.org/#search%7Cga%7C1%7Cg%3A%22com.io7m.brackish%22)
[![Maven Central (snapshot)](https://img.shields.io/maven-metadata/v?metadataUrl=https%3A%2F%2Fcentral.sonatype.com%2Frepository%2Fmaven-snapshots%2Fcom%2Fio7m%2Fbrackish%2Fcom.io7m.brackish%2Fmaven-metadata.xml&style=flat-square)](https://central.sonatype.com/repository/maven-snapshots/com/io7m/brackish/)
[![Codecov](https://img.shields.io/codecov/c/github/io7m-com/brackish.svg?style=flat-square)](https://codecov.io/gh/io7m-com/brackish)
![Java Version](https://img.shields.io/badge/25-java?label=java&color=5ce67e)

![com.io7m.brackish](./src/site/resources/brackish.jpg?raw=true)

| JVM | Platform | Status |
|-----|----------|--------|
| OpenJDK (Temurin) Current | Linux | [![Build (OpenJDK (Temurin) Current, Linux)](https://img.shields.io/github/actions/workflow/status/io7m-com/brackish/main.linux.temurin.current.yml)](https://www.github.com/io7m-com/brackish/actions?query=workflow%3Amain.linux.temurin.current)|
| OpenJDK (Temurin) LTS | Linux | [![Build (OpenJDK (Temurin) LTS, Linux)](https://img.shields.io/github/actions/workflow/status/io7m-com/brackish/main.linux.temurin.lts.yml)](https://www.github.com/io7m-com/brackish/actions?query=workflow%3Amain.linux.temurin.lts)|
| OpenJDK (Temurin) Current | Windows | [![Build (OpenJDK (Temurin) Current, Windows)](https://img.shields.io/github/actions/workflow/status/io7m-com/brackish/main.windows.temurin.current.yml)](https://www.github.com/io7m-com/brackish/actions?query=workflow%3Amain.windows.temurin.current)|
| OpenJDK (Temurin) LTS | Windows | [![Build (OpenJDK (Temurin) LTS, Windows)](https://img.shields.io/github/actions/workflow/status/io7m-com/brackish/main.windows.temurin.lts.yml)](https://www.github.com/io7m-com/brackish/actions?query=workflow%3Amain.windows.temurin.lts)|

## brackish

A JavaFX component for rendering waveforms.

## Features

* Render waveforms in realtime.
* Zoom and scroll waveforms.
* Written in pure Java 25.
* [OSGi-ready](https://www.osgi.org/)
* [JPMS-ready](https://en.wikipedia.org/wiki/Java_Platform_Module_System)
* ISC license.

## Usage

Add a `WaveView` to your JavaFX layouts. Implement the `WaveModelType` interface
to allow the application to sample waveforms.

## Demo

A [demo application](com.io7m.brackish.demo) is included.

![Brackish](src/site/resources/brackish2.png)

