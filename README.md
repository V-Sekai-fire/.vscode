# .vscode

A code editor configuration that builds and debugs the Godot editor from a workspace whose engine source sits in `godot/`.

## What it is for

A default build task runs scons for a `platform=macos` editor build with tests and a compilation database, and a launch configuration starts the arm64 editor binary under LLDB. A settings file silences the source control view's warning about too many changes.

## Use

Clone it as `.vscode/` at the root of a workspace that holds the engine source in `godot/`.

## Licence

MIT. See [LICENSE](LICENSE).
