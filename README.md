# TUI Java Test

A small demo application that tests Lanterna-based terminal user interfaces in Java.

[![Java CI](https://github.com/Project516/TUIJavaTest/actions/workflows/gradle.yml/badge.svg)](https://github.com/Project516/TUIJavaTest/actions/workflows/gradle.yml)

## What it does

The app opens a terminal window with:

- A "Hello" label
- A button that opens a second window
- An exit button

It is a minimal test of Lanterna's GUI2 framework (panels, buttons, multi-window support).

## Requirements

- Java 25 or newer ([Eclipse Temurin](https://adoptium.net/temurin) recommended)
- A terminal that supports TUI rendering

## Build and run

```sh
./gradlew build
java -jar app/build/libs/app-all.jar
```

Or use the convenience script:

```sh
./test.sh
```

## Project structure

```
app/
  build.gradle          Application, Shadow, and Spotless config
  src/main/java/dev/project516/TUIJavaTest/
    Main.java           Entry point, sets up Lanterna GUI
settings.gradle        Root project settings
```
