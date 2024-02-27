# Retro programs Scoop Bucket

[![Tests](https://github.com/filip2cz/scoop-retro/actions/workflows/ci.yml/badge.svg)](https://github.com/filip2cz/scoop-retro/actions/workflows/ci.yml) [![Excavator](https://github.com/filip2cz/scoop-retro/actions/workflows/excavator.yml/badge.svg)](https://github.com/filip2cz/scoop-retro/actions/workflows/excavator.yml)

## How do I install anything from here?

1. Install scoop if you did not already
```pwsh
Set-ExecutionPolicy -ExecutionPolicy RemoteSigned -Scope CurrentUser; Invoke-RestMethod -Uri https://get.scoop.sh | Invoke-Expression
```

2. Add this bucket into scoop
```pwsh
scoop bucket add scoop-retro https://github.com/filip2cz/scoop-retro
```

3. Install app you want
```pwsh
scoop install scoop-retro/<manifestname>
```

### After this, you don't have to do first and second step again! Just install anything you want

## Games list

| Game name         | manifestname  |
| ----------------- | ------------- |
| Doom 2            | doom2         |
| Wolfenstein 3D    | Wolfenstein3D |

## Other software list

| Software          | manifestname      |
| ----------------- | ----------------- |
| AutoCAD 2.18      | AutoCAD-2_18      |
| Super Fdisk setup | SuperFdiskSetup   |

## How do I contribute new manifests?

To make a new manifest contribution, please read the [Contributing
Guide](https://github.com/ScoopInstaller/.github/blob/main/.github/CONTRIBUTING.md)
and [App Manifests](https://github.com/ScoopInstaller/Scoop/wiki/App-Manifests)
wiki page.
