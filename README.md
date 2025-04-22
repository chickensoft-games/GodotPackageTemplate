# GodotPackageTemplate

[![Chickensoft Badge][chickensoft-badge]][chickensoft-website] [![Discord][discord-badge]][discord] [![Read the docs][read-the-docs-badge]][docs]

A .NET template for quickly creating a C# nuget package for use with Godot 4.

```sh
# Install this template
dotnet new --install Chickensoft.GodotPackage

# Generate a new project based on this template
dotnet new chickenpackage --name "MyPackageName" --param:author "My Name"
```

**NOTE:** This repository contains only the `dotnet new` template information and package description. The actual template contents are included as a git submodule from the [GodotPackage] repository.

The [GodotPackage] template contents are included as a submodule, since it is easier to verify changes to the template if it compiles and bundles into a package of its own.

Microsoft has an article on [creating template packages][create-template-package].

<!-- Links -->

<!-- Header -->
[chickensoft-badge]: https://chickensoft.games/img/badges/chickensoft_badge.svg
[chickensoft-website]: https://chickensoft.games
[discord-badge]: https://chickensoft.games/img/badges/discord_badge.svg
[discord]: https://discord.gg/gSjaPgMmYW
[read-the-docs-badge]: https://chickensoft.games/img/badges/read_the_docs_badge.svg
[docs]: https://chickensoft.games/docs/

<!-- Article -->
[GodotPackage]: https://github.com/chickensoft-games/GodotPackage
[create-template-package]: https://learn.microsoft.com/en-us/dotnet/core/tutorials/cli-templates-create-template-package
