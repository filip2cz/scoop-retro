# Retro programs Scoop Bucket

[![Tests](https://github.com/filip2cz/scoop-retro/actions/workflows/ci.yml/badge.svg)](https://github.com/filip2cz/scoop-retro/actions/workflows/ci.yml) [![Excavator](https://github.com/filip2cz/scoop-retro/actions/workflows/excavator.yml/badge.svg)](https://github.com/filip2cz/scoop-retro/actions/workflows/excavator.yml)

![Visitors](https://api.visitorbadge.io/api/daily?path=https%3A%2F%2Fgithub.com%2Ffilip2cz%2Fscoop-retro&label=VISITORS%20TODAY&countColor=%23263759)

## Setup

Just paste commands below into Powershell

1. Install scoop if you did not already
```pwsh
Set-ExecutionPolicy -ExecutionPolicy RemoteSigned -Scope CurrentUser; Invoke-RestMethod -Uri https://get.scoop.sh | Invoke-Expression
```

2. Add this bucket and buckets with dependencies (emulators, etc.) into scoop
```
scoop bucket add main; scoop bucket add extras; scoop bucket add games; scoop bucket add filip2cz_scoop-retro https://github.com/filip2cz/scoop-retro
```

## Usage

In powershell, execute this command:
```
scoop update; scoop install filip2cz_scoop-retro/<manifestname>
```

Use manifestname from tables below instead of `<manifestname>`.

## Games list

| Game name                                 | manifestname          | Platform  | Runtime                               | Language  | Notes |
| ----------------------------------------- | --------------------- | --------- | ------------------------------------- | --------- | ----- |
| 3D Pinball                                | Pinball               | Win x86   | native                | English | Version from Windows XP |
| Bang! Bang!                               | BangBang              | PalmOS    | emulator - Mu with Retroarch          | English   |       |
| Bulánci                                   | Bulanci               | Win x86   | native                                | Czech     |       |
| Cervii                                    | Cervii                | MS-DOS    | emulator - DOSBox                     | English   |       |
| Contra                                    | Contra                | NES       | emulator - Mesen                      | English   |       |
| Doom                                      | Doom                  | MS-DOS    | emulator - DOSBox                     | English   |       |
| Doom 2                                    | Doom2                 | MS-DOS    | emulator - DOSBox                     | English   |       |
| Driver            | Driver | Win x86 | native | English | If it crashes, you can run it in compatability mode - Windows XP service pack 3 |
| Duke Nukem 3D                             | duke3d                | MS-DOS    | emulator - DOSBox                     | English   |       |
| Dyna Blaster                              | DynaBlaster   | MS-DOS | emulator - DOSBox | English   | This game is also known as Bomberman |
| Fallout Van Buren      | FalloutVanBuren | Win x86 | native | English   | This game was canceled after bankrupt, so this is only playtest |
| F1 Race                                   | f1race                | NES       | emulator - Mesen                      | English   |       |
| Grand Theft Auto                         | GrandTheftAuto         | MS-DOS    | emulator - DOSBox                     | English   |       |
| Minesweeper                               | minesweeper           | Win x86   | native                | English | Version from Windows XP |
| Minesweeper / Hledání min                 | minesweeper-cz        | Win x86   | native                | Czech   | Version from Windows XP |
| Need for Speed                            | needforspeed          | MS-DOS    | emulator - DOSBox                     | English   |       |
| Plants vs Zombies                         | PlantsVsZombies       | Win x86   | native | English | Version with good old dancing zombies  |
| Playboy                                   | playboy               | MS-DOS    | emulator - DOSBox                     | Czech     |       |
| PortaMonkey                               | PortaMonkey           | PalmOS    | emulator - Mu with Retroarch          | English   |       |
| Solitaire + Spider Solitaire              | solitaire             | Win x86   | native                | English | Version from Windows XP |
| Solitaire + Spider Solitaire              | solitaire-cz          | Win x86   | native                | Czech   | Version from Windows XP |
| Super Mario Bros.                         | SuperMarioBros        | NES       | emulator - Mesen                      | English   |       |
| Super Mario Bros. 2                       | SuperMarioBros2       | NES       | emulator - Mesen                      | English   |       |
| Super Mario Land                          | SuperMarioLand        | GameBoy   | emulator - bgb                        | English   |       |
| Tetris                                    | Tetris                | NES       | emulator - Mesen                      | English   |       |
| Tetris Attack                             | tetris-attack         | SNES      | emulator - Snes9x                     | English   |       |
| The Residents: Freak Show                 | freakshow             | Win 3.1   | emulator - DOSBox with Windows 3.1    | English   |       |
| The Settlers II 10th Anniversary Czech    | settlers2-remake-cz   | Win x86   | native                                | Czech     |       |
| Vlak                                      | Vlak                  | MS-DOS    | emulator - DOSBox                     | Czech     |       |
| Wolfenstein 3D                            | Wolfenstein3D         | MS-DOS    | emulator - DOSBox                     | English   |       |

## Other software list

| Software                  | manifestname      | Platform | Runtime           | Language  | Notes |
| ------------------------- | ----------------- | -------- | ----------------- | --------- | - |
| AutoCAD 2.18 | AutoCAD-2_18 | MS-DOS | emulator - DOSBox | English | Recommended config: Default, except Graphic Display -> 2; Digitizer -> 19 |
| Johnny Castaway           | JohnnyCastaway    | Win 3.1  | emulator - DOSBox | English   | alternative name: The Adventures of Johnny Castaway |
| MS Paint - Win XP         | mspaint-xp        | Win x86  | native            | English   | |
| MS Paint - Win XP Czech   | mspaint-xp-cz     | Win x86  | native            | Czech     | |
| Super Fdisk setup         | SuperFdiskSetup   | Win x86  | native            | English   | |
| Windows 3.1               | Windows-3_1       | MS-DOS   | emulator - DOSBox | English   | |
| Windows 3.1 Czech         | Windows-3_1-cz    | MS-DOS   | emulator - DOSBox | Czech     | |

## How do I contribute new manifests?

To make a new manifest contribution, please read the [App Manifests](https://github.com/ScoopInstaller/Scoop/wiki/App-Manifests) wiki page.

## FAQ

### How can I launch my software?
You should have icon in your start menu. If you can't find it, try to find `Scoop Apps` folder in start menu.

### Where it is installed?
Apps are installed by default into scoop folder in your home directory.

### Isn't it virus?
This repo is not any software technically. It is just instructions for Scoop (https://scoop.sh/) where to download things. Scoop is not virus, it is opensource and community trusted software. Games and software is mostly downloaded from archive.org, you can everytime check if you trust source with command `scoop cat <manifestname>` and find download url.

### What is source of this software?
Games and software is mostly downloaded from archive.org, you can everytime check if you trust source with command `scoop cat <manifestname>` and find download url.
