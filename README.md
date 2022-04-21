# Kicad-Library

__Shared (custom) files between KiCad projects such as:__  
- Footprints (incl. 3d models)
- Schematic Symbols
- Drawing-Sheets
- KiBot configurations
- and anything alike

## Usage
Include this repo as a submodule in your KiCad projects root folder, and update the projects libraries to point there.

Alternatively base your new KiCad project on [this template](https://github.com/krsche/kicad-template)

## Contributions

I'm happy about any PRs, Fork, etc. but please keep the following in mind if you want to contribute:
- Follow the existing style of the repo
- Write proper commit messages and PR descriptions
- For any 3rd party component the source needs to be specified, see [3rd-party/README.md](3rd-party/README.md)

## ToDo
- Add GH Actions for checking
  - Commit messages
  - Generating Releases (semantic-versioning)
  - Running checks similar to KiCad's orig footprint/symbol library check pipelines
  - KiBot tests (via kicad-template repo?)