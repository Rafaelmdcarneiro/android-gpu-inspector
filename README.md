# Android GPU Inspector

## About

Visit [gpuinspector.dev](https://gpuinspector.dev) for information about Android GPU Inspector.

The [developer documentation](DEVDOC.md) contains some hints for AGI
developers. See also the README files under some source directories.

## Downloads

**[Download the latest version of AGI here.](https://github.com/google/agi/releases)**

*Unstable* developer releases are [here](https://github.com/google/agi-dev-releases/releases).

Dependencies for Linux builds in zip archives:
- openjdk-11-jre 
- libgtk-3-0
- libwebkit2gtk

These are marked as dependencies in the .deb package. 

If you install AGI via a zip archive, make sure to install these dependencies as well.

## Building

**See [Building Android GPU Inspector](BUILDING.md).**

## Running the client

After building AGI, you can run the client from `<agi-root>/bazel-bin/pkg/agi`.
