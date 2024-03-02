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

| Game name                 | manifestname      | Runtime                               | Language  |
| ------------------------- | ----------------- | ------------------------------------- | --------- |
| Cervii                    | Cervii            | emulator - DOSBox                     | English   |
| Doom                      | Doom              | emulator - DOSBox                     | English   |
| Doom 2                    | Doom2             | emulator - DOSBox                     | English   |
| Duke Nukem 3D             | duke3d            | emulator - DOSBox                     | English   |
| Super Mario Bros.         | SuperMarioBros    | emulator - Mesen                      | English   |
| Tetris                    | Tetris            | emulator - Mesen                      | English   |
| The Residents: Freak Show | freakshow         | emulator - DOSBox with Windows 3.1    | English   |
| Vlak                      | Vlak              | emulator - DOSBox                     | Czech     |
| Wolfenstein 3D            | Wolfenstein3D     | emulator - DOSBox                     | English   |

## Other software list

| Software                  | manifestname      | Runtime           | Language  |
| ------------------------- | ----------------- | ----------------- | --------- |
| AutoCAD 2.18              | AutoCAD-2_18      | emulator - DOSBox | English   |
| MS Paint - Win XP         | mspaint-xp        | native            | English   |
| MS Paint - Win XP Czech   | mspaint-xp-cz     | native            | Czech     |
| Super Fdisk setup         | SuperFdiskSetup   | native            | English   |
| Windows 3.1               | Windows-3_1       | emulator - DOSBox | English   |
| Windows 3.1 Czech         | Windows-3_1-cz    | emulator - DOSBox | Czech     |

## How do I contribute new manifests?

To make a new manifest contribution, please read the [Contributing
Guide](https://github.com/ScoopInstaller/.github/blob/main/.github/CONTRIBUTING.md)
and [App Manifests](https://github.com/ScoopInstaller/Scoop/wiki/App-Manifests)
wiki page.