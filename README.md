<p align="center">
    <a href=""><img src="docs/github/images/logo.svg" alt="Logo" height="128px" /></a>
</p>

<h1 align="center">Apple Siri Voice Navigation - English</h1>
<!--
<p align="center">
    <a href="/LICENSE"><img alt="GitHub License" src="https://img.shields.io/github/license/quinn0823/apple-siri-voice-navigation"></a>
    <a href="https://github.com/quinn0823/apple-siri-voice-navigation/releases/latest/"><img alt="GitHub Release" src="https://img.shields.io/github/v/release/quinn0823/apple-siri-voice-navigation"></a>
    <a href="https://buymeacoffee.com/jonathanchiu"><img alt="Buy Me A Coffee" src="https://img.shields.io/badge/buy me a coffee-jonathanchiu-ffdd00?logo=buymeacoffee"></a>
</p>-->
<!--
<p align="center">
    <a href="https://steamcommunity.com/sharedfiles/filedetails/?id=3404021712"><img alt="Steam (ETS2)" src="https://img.shields.io/badge/Steam (ETS2)-subscribe-799905?logo=steam&labelColor=1b2838"></a>
    <a href="https://steamcommunity.com/sharedfiles/filedetails/?id=3404021712"><img alt="Steam Subscriptions" src="https://img.shields.io/steam/subscriptions/3404021712"></a>
    <a href="https://steamcommunity.com/sharedfiles/filedetails/?id=3404021712"><img alt="Steam Downloads" src="https://img.shields.io/steam/downloads/3404021712"></a>
    <a href="https://steamcommunity.com/sharedfiles/filedetails/?id=3404021712"><img alt="Steam Favorites" src="https://img.shields.io/steam/favorites/3404021712"></a>
</p>-->

<!--<p align="center">
    <a href="https://steamcommunity.com/sharedfiles/filedetails/?id=3404022298"><img alt="Steam (ATS)" src="https://img.shields.io/badge/Steam (ATS)-subscribe-799905?logo=steam&labelColor=1b2838"></a>
    <a href="https://steamcommunity.com/sharedfiles/filedetails/?id=3404022298"><img alt="Steam Subscriptions" src="https://img.shields.io/steam/subscriptions/3404022298"></a>
    <a href="https://steamcommunity.com/sharedfiles/filedetails/?id=3404022298"><img alt="Steam Downloads" src="https://img.shields.io/steam/downloads/3404022298"></a>
    <a href="https://steamcommunity.com/sharedfiles/filedetails/?id=3404022298"><img alt="Steam Favorites" src="https://img.shields.io/steam/favorites/3404022298"></a>
</p>

<p align="center">
    <a href="https://github.com/quinn0823/apple-siri-voice-navigation/releases/latest/"><img alt="GitHub" src="https://img.shields.io/badge/GitHub-download-4493f8?logo=github&labelColor=181717"></a>
    <a href="https://www.nexusmods.com/eurotrucksimulator2/mods/173"><img alt="Nexus Mods (ETS2)" src="https://img.shields.io/badge/Nexus Mods (ETS2)-download-d98f40?labelColor=29292e"></a>
    <a href="https://www.nexusmods.com/americantrucksimulator/mods/77"><img alt="Nexus Mods (ATS)" src="https://img.shields.io/badge/Nexus Mods (ATS)-download-d98f40?labelColor=29292e"></a>
</p>-->

**Experience the road with Siri!** Siri Voice Navigation brings the iconic voices from Apple to truck simulator games. With **20 voices** to choose from, Siri is here to guide your trucking adventures, making your journey more enjoyable and memorable.

**January 25 (4.5)**: Siri is now **compatible with multiplayer** (optional).

---

## Introduction

I speak English, so having a mod that has a whole bunch of voices instead of just english ones takes up extra space on my system. So, I decided to fork the repo and remove all the voices, except the english ones. If you want to contribute to this project, I suggest you do so upstream at [https://github.com/quinn0823/apple-siri-voice-navigation/]

## Voices [20 Voices in English]

Supports English.

### Available

- English (Australia) - Siri (Voice 1)
- English (Australia) - Siri (Voice 2)
- English (Australia) - Siri (Voice 3)
- English (Australia) - Siri (Voice 4)
- English (India) - Siri (Voice 1)
- English (India) - Siri (Voice 2)
- English (Ireland) - Siri (Voice 1)
- English (Ireland) - Siri (Voice 2)
- English (Scotland, United Kingdom) - Fiona (Enhanced)
- English (South Africa) - Siri (Voice 1)
- English (South Africa) - Siri (Voice 2)
- English (United Kingdom) - Siri (Voice 1)
- English (United Kingdom) - Siri (Voice 2)
- English (United Kingdom) - Siri (Voice 3)
- English (United Kingdom) - Siri (Voice 4)
- English (United States) - Siri (Voice 1)
- English (United States) - Siri (Voice 2)
- English (United States) - Siri (Voice 3)
- English (United States) - Siri (Voice 4)
- English (United States) - Siri (Voice 5)

## Compatibility

**1.43+**, multiplayer compatible (optional).

<!--
## Download

- **Workshop** (Recommended): [ETS2](https://steamcommunity.com/sharedfiles/filedetails/?id=3404021712), [ATS](https://steamcommunity.com/sharedfiles/filedetails/?id=3404022298)
- GitHub: [Releases](https://github.com/quinn0823/apple-siri-voice-navigation/releases/latest) / [Build from source](#build-from-source)
- Nexus Mods: [ETS2](https://www.nexusmods.com/eurotrucksimulator2/mods/173), [ATS](https://www.nexusmods.com/americantrucksimulator/mods/77)-->

## Build from Source

1. Install the following dependencies:
    - Git (Optional)
    - [Python 3.6+](https://www.python.org/downloads/)
1. Clone the repository or download the source.
    ```
    git clone https://github.com/quinn0823/apple-siri-voice-navigation.git
    ```
1. Change directory to the source folder and run the build script.
    ```
    cd apple-siri-voice-navigation
    python scripts/build.py
    ```
1. The built standard mod will be located in `build/standard`.


## Usage

1. Move **apple-siri-voice-navigation.zip** to the mod folder:
    - Windows
        - ETS2: `%UserProfile%\Documents\Euro Truck Simulator 2\mod`
        - ATS: `%UserProfile%\Documents\American Truck Simulator\mod`
    - macOS (Press **Shift-Command-G** in Finder and then paste)
        - ETS2: `~/Library/Application Support/Euro Truck Simulator 2/mod`
        - ATS: `~/Library/Application Support/American Truck Simulator/mod`
    - Linux
        - ETS2: `~/.local/share/Euro Truck Simulator 2/mod`
        - ATS: `~/.local/share/American Truck Simulator/mod`
1. Click **Mods** on the title screen to open the mod manager.
1. Double-click **Apple Siri Voice Navigation** to activate this mod.
1. Open **Options**.
1. Go to **Audio > Voice Navigation > Language and voice** and then select a voice you like.

---

## If You Want More Voices in Other Languages...

Please **leave your request** on **upstream**. That is, [here](https://github.com/quinn0823/apple-siri-voice-navigation/).

## If You Find a Mistake...

Please **leave a comment**, **create a new issue**, or directly **make a correction here**. I don't speak all of these languages. Although I've tried my best to ensure accuracy, there may still be mistakes.

Please do so upstream! [Click here](https://github.com/quinn0823/apple-siri-voice-navigation/)


### File Structure

```
apple-siri-voice-navigation
├── * build                  // (Ignored) Files built by build scripts
│   └── * standard           // (Ignored) Standard mod
│       └── * apple-siri-voice-navigation.zip   // (Ignored) Refer to Usage section
├── docs
│   ├── github               // Documentation for GitHub
│   │   ├── images
│   │   ├── readme
│   │   └── release_notes
│   ├── mod                  // Documentation for Mod Manager in-game
│   │   ├── descriptions
│   │   └── images
│   └── workshop             // Documentation for Workshop
│       ├── change_notes
│       ├── descriptions
│       └── images
├── navigation
│   ├── build                // BANK and GUID files built by FMOD Studio, with SII files
│   ├── commands             // Navigation commands
│   │   ├── ...              // Commands in each language
│   │   └── template.json    // A template with no content
│   └── projects             // FMOD Studio projects
│       └── template.zip     // Sound project template
├── scripts                  // Scripts for building the mod
│   ├── build.py             // Script in Python
│   ├── * config.ini         // (Ignored) User config file
│   └── config_default.ini   // Default config file
└── LICENSE                  // The GNU General Public License v3.0 (GPL-3.0)
```

### Regular Expressions

#### Update the Version Number

Search

``` regexp
(?<=\(|\*{2}|\])\d+\.\d+(\.\d+)?(?=\)|\*{2}|\[)
```

Replace

```
${version_number}
```

#### Remove Bold and Color Tags

Search

``` regexp
(\*{2}|\[\w+\])((\S+) ?\S(日本)\S ?- (\S+)( ?\S+( ?\d)?\S)?)(\*{2}|\[/?\w+\])
```

Replace

```
$2
```

#### Add Bold or Color Tags

- **GitHub**

    Search

    ``` regexp
    - ((\S+) ?\S(日本)\S ?- (\S+)( ?\S+( ?\d)?\S)?)
    ```

    Replace

    ```
    - **$1**
    ```

- **Workshop (BBCode)**

    Search

    ``` regexp
    \[\*\]((\S+) ?\S(日本)\S ?- (\S+)( ?\S+( ?\d)?\S)?)
    ```

    Replace

    ```
    [*][b]$1[/b]
    ```

- **Mod**

    Search

    ``` regexp
    \* ((\S+) ?\S(日本)\S ?- (\S+)( ?\S+( ?\d)?\S)?)
    ```

    Replace

    - Green (Added)

        ```
        * [green]$1[normal]
        ```

    - Blue (Improved)

        ```
        * [blue]$1[normal]
        ```


---

Release Date: XX XX, 2026 (4.5-eng)

Published Date (GitHub): May 3, 2026

The GNU General Public License v3.0 (GPL-3.0)

Copyright © 2025, 2026 Jonathan Chiu

Copyright © 2026 Jake Thomas

Forked from Jonathan Chiu's main repo, which you can find by clicking the blue link under the repo title.
