# libopus

[![Version](https://img.shields.io/nuget/vpre/libopus)](https://www.nuget.org/packages/libopus)

Pre-built binaries for [libopus](https://opus-codec.org).

## Features

| Property                         | Default                                                  | Description                                                                                           |
| -------------------------------- | -------------------------------------------------------- | ----------------------------------------------------------------------------------------------------- |
| `$(LibOpusEnableRuntimeLinking)` | `true`                                                   | Toggle whether shared libraries are copied to the output directory.                                   |
| `$(LibOpusEnableStaticLinking)`  | `$(PublishAot) == 'true' AND $(RuntimeIdentifier) != ''` | Toggle whether `DirectPInvoke`+`NativeLibrary` items are included in the project (for Static Linking) |