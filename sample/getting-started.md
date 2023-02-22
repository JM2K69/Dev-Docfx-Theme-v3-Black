---
title: Getting Started
---
## Getting Started
`DocFX V3-Beta`

- Install [.NET Core](https://www.microsoft.com/net/download)
- Install latest `docfx` pre release:
```powershell
dotnet tool update -g docfx --version "3.0.0-*" --add-source https://docfx.pkgs.visualstudio.com/docfx/_packaging/docs-public-packages/nuget/v3/index.json
```

Please ensure that you are using DocFX v3 beta. This theme will not work for DocFX v2 (the current stable one).

## Create a blank site
- Create a directory for your website:
```powershell
mkdir my-website
cd my-website
```
- Create a new website:
```powershell
docfx new conceptual
```
- Edit or create a docfx.yml
```yml
template: https://github.com/JM2K69/Docfx-Theme-v3-Black
exclude:
- specs/**
globalMetadata:
  titleSuffix: docfx
  menu_path: /menu.json
  _appLogoPath: /favicon.ico
  _appFooter: <span>Copyright © 2022 JM2K69 - <strong>DocFX</strong></span>
  _appTitle: Blank site
  _enableSearch: false
  _disableContribution: true
  _enableNewTab: true
```
- Build your website.
```powershell
docfx build
```
- Start a local HTTP static file server in `_site` folder. 
```powershell
docfx serve
```
- Browse the url http://localhost:8080 


## Development

### Prerequisites

```
- Yarn
- Node 17.x
- DocFX V3-Beta
```

Please ensure that you are using DocFX v3 beta, and have it installed globally! This theme will not work for DocFX v2 (the current stable one).

#### Building

1. Run `yarn` in project root.
2. Run `yarn run start` to start the development environment.
3. When ready, run `yarn run build` and `yarn run copy`. This will place your built template into `build/`.

## License

This project is licensed under the MIT license, see the [LICENSE]() file for details.

## Credits

Original theme by DocFX team.