<!--lint ignore awesome-heading-->
# Awesome goome [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

<a href="https://goome-ui.github.io/docs/"><img src="https://raw.githubusercontent.com/goome-ui/.github/main/profile/logo.png" align="right" width="100" alt="goome"></a>

> See-through, always on top overlays and UI in C, with C#, Python, Java and Godot bindings.

goome draws on a click-through layer over every other window. Only what you draw takes clicks, the rest goes to whatever is under it. It runs on Linux (X11 and Wayland), Windows and macOS, and it also works inside games and engines.

## Contents

- [Official](#official)
- [Apps](#apps)
- [Templates and Tools](#templates-and-tools)
- [Mods and Engines](#mods-and-engines)
- [Examples](#examples)
- [Docs and Guides](#docs-and-guides)
- [Community](#community)
- [Made with goome](#made-with-goome)

## Official

- [c-goome](https://github.com/goome-ui/c-goome) - The C99 library, a single header with no dependencies.
- [csharp-goome](https://github.com/goome-ui/csharp-goome) - C# bindings for .NET 8 with a Unity package.
- [python-goome](https://github.com/goome-ui/python-goome) - Python bindings over ctypes, nothing to build.
- [java-goome](https://github.com/goome-ui/java-goome) - Java 22+ bindings over FFM or LWJGL.
- [godot-goome](https://github.com/goome-ui/godot-goome) - GDExtension addon for Godot.

## Apps

Ready to use downloads for Linux, Windows and macOS are on the [examples release](https://github.com/goome-ui/examples/releases/latest).

- [goome-hud](https://github.com/goome-ui/examples/tree/main/apps/goome-hud) - CPU, RAM, network and temps in a corner of the screen.
- [crosshair](https://github.com/goome-ui/examples/tree/main/apps/crosshair) - Overlay with crosshair styles, colors and a settings window.
- [sticky](https://github.com/goome-ui/examples/tree/main/apps/sticky) - Notes stuck over the desktop, pinned or click-through.
- [keyviz](https://github.com/goome-ui/examples/tree/main/apps/keyviz) - Shows keys and clicks on screen for tutorials and recordings.

## Templates and Tools

- [goome-cli](https://github.com/goome-ui/goome-cli) - `goome new` makes a project from a template in any of the languages.
- [goome-app-template-c](https://github.com/goome-ui/goome-app-template-c) - C app with an overlay toggle, plus overlay, mod menu and HUD versions.
- [goome-app-template-csharp](https://github.com/goome-ui/goome-app-template-csharp) - C# app with the same four starting points.
- [goome-app-template-python](https://github.com/goome-ui/goome-app-template-python) - Python app with the same four starting points.
- [goome-app-template-java](https://github.com/goome-ui/goome-app-template-java) - Java app with the same four starting points.
- [goome-app-template-godot](https://github.com/goome-ui/goome-app-template-godot) - Godot app panel that turns into a window over the game.
- [UI builder](https://goome-ui.github.io/docs/builder/) - Drag a layout together in the browser and copy the code out.

## Mods and Engines

- [Native mod kit](https://github.com/goome-ui/examples/tree/main/mods/native) - DLL mod menus for Windows games over DirectX 11, DirectX 12, OpenGL and Vulkan.
- [Unity mods](https://github.com/goome-ui/csharp-goome/tree/main/mods) - Mod menu and templates for BepInEx 5, BepInEx 6 and MelonLoader.
- [Minecraft mods](https://github.com/goome-ui/java-goome/tree/main/minecraft) - Fabric and NeoForge mods that draw goome in the game.
- [Godot addon](https://github.com/goome-ui/godot-goome/tree/main/addons/goome) - The addon folder to drop into a Godot project.
- [raylib](https://github.com/goome-ui/examples/tree/main/engines/raylib) - Offscreen goome drawn in raylib's GL context.
- [SDL2 + OpenGL 3](https://github.com/goome-ui/examples/tree/main/engines/sdl_gl3) - The SDL platform backend with the GL3 renderer.
- [LÖVE](https://github.com/goome-ui/examples/tree/main/engines/love2d) - LuaJIT ffi to the goome shared library inside love2d.

## Examples

- [C examples](https://github.com/goome-ui/examples/tree/main/c) - Clock, todo, launcher, region shot, dashboard and more.
- [C# examples](https://github.com/goome-ui/examples/tree/main/csharp) - Hello app, contacts, themes, timer and more in C#.
- [Python examples](https://github.com/goome-ui/examples/tree/main/python) - Hello overlay, color picker, crosshair and more in Python.
- [Unity sample](https://github.com/goome-ui/examples/tree/main/unity) - Unity project using the goome package.
- [Godot example](https://github.com/goome-ui/godot-goome/tree/main/example) - Godot project with a menu, a skinned window and a game overlay.

## Docs and Guides

- [Docs](https://goome-ui.github.io/docs/) - Everything about goome in one site.
- [Getting started in C](https://goome-ui.github.io/docs/start-c/) - First overlay in C.
- [Getting started in C#](https://goome-ui.github.io/docs/start-csharp/) - First overlay in C#.
- [Getting started in Python](https://goome-ui.github.io/docs/start-python/) - First overlay in Python.
- [Getting started in Java](https://goome-ui.github.io/docs/start-java/) - First overlay in Java.
- [Getting started in Godot](https://goome-ui.github.io/docs/start-godot/) - First overlay in Godot.
- [Getting started in Unity](https://goome-ui.github.io/docs/start-unity/) - First overlay in Unity.
- [The three modes](https://goome-ui.github.io/docs/modes/) - Overlay, window and offscreen modes.
- [UI kit](https://goome-ui.github.io/docs/ui/) - How the built in widgets work.
- [How mods work](https://goome-ui.github.io/docs/mods/) - Mods for games and engines, and the anti-cheat line.
- [Templates and goome new](https://goome-ui.github.io/docs/templates/) - Starting a project from a template.
- [Where it works](https://goome-ui.github.io/docs/platforms/) - Desktops, compositors and what each one supports.
- [FAQ](https://goome-ui.github.io/docs/faq/) - Common questions.

## Community

- [Discussions](https://github.com/goome-ui/c-goome/discussions) - Questions and things people made.
- [Good first issues](https://goome-ui.github.io/docs/community/#good-first-issues) - Small issues in every main repo to start with.
- [Made with goome badge](https://goome-ui.github.io/docs/badges/) - README badges for projects that use goome.
- [Community page](https://goome-ui.github.io/docs/community/) - Where to ask, help out and show stuff.

## Made with goome

Made something with goome? Add yours with a PR.

- [goome-hud download](https://goome-ui.github.io/docs/downloads/#goome-hud) - System stats HUD for the desktop.
- [crosshair download](https://goome-ui.github.io/docs/downloads/#crosshair) - Aim overlay for any game.
- [sticky download](https://goome-ui.github.io/docs/downloads/#sticky) - Notes that sit on top of everything.
- [keyviz download](https://goome-ui.github.io/docs/downloads/#keyviz) - Key and click viewer for recordings.
- [Sev's Mod Manager](https://github.com/sevvy-wevvy/sevs-mod-manager) - Mod manager for nearly any Unity game (Gorilla Tag, ULTRAKILL, REPO, BONELAB and more) on Linux, Windows and macOS, with three layouts and five themes.

## Contributing

Contributions are welcome! Read the [contributing guide](contributing.md) first.

Thanks to everyone who helped out:

<a href="https://github.com/goome-ui/awesome-goome/graphs/contributors"><img src="https://contrib.rocks/image?repo=goome-ui/awesome-goome" alt="contributors"></a>
