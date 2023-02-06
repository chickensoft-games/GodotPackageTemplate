# GodotPackageTemplate

[![Chickensoft Badge][chickensoft-badge]][chickensoft-website] [![Discord][discord-badge]][discord]

A .NET template for quickly creating a C# nuget package for use with Godot 4.

```sh
# Install this template
dotnet new --install Chickensoft.GodotPackage

# Generate a new project based on this template
dotnet new godotpackage --name "MyPackageName" --param:author "My Name"
```

**NOTE:** This repository contains only the `dotnet new` template information and package description. The actual template contents are included as a git submodule from the [GodotPackage] repository.

The [GodotPackage] template contents are built as an app themselves, allowing the template to be easily maintained and updated as if it were a project itself.

<!-- Links -->

<!-- Header -->
[chickensoft-badge]: https://chickensoft.games/images/chickensoft/chickensoft_badge.svg
[chickensoft-website]: https://chickensoft.games
[discord]: https://discord.gg/gSjaPgMmYW
[discord-badge]: https://img.shields.io/badge/Chickensoft%20Discord-%237289DA.svg?style=flat&logo=discord&logoColor=white

<!-- Article -->
[GodotPackage]: https://github.com/chickensoft-games/GodotPackage
