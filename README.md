<p align="center">
  <img 
    src="https://github.com/user-attachments/assets/b99ea052-79bd-44ab-8111-5a11496a973d"
    alt="Reforest Revenge Logo" 
    width="700"
  />
</p>

**Reforest Revenge** is a 2D Unity platformer game created for **Global Game Jam 2023**. The game follows **Rooty**, a supernatural forest creature born from the roots of cut-down trees, whose mission is to restore nature in a world damaged by deforestation.

The project combines platformer gameplay, forest-themed visuals, animated characters, enemies, collectibles, UI menus, audio, and multiple game scenes.

> [!NOTE]
> This project was developed as part of **Global Game Jam 2023**, using the theme **"Roots"**.

---

## Global Game Jam Entry

This game was submitted to Global Game Jam 2023.

| Item | Details |
|---|---|
| Game | `Reforest Revenge` |
| Jam Year | `2023` |
| Theme | `Roots` |
| Jam Site | `Innovaction TEC Puebla` |
| Platform | `MS Windows` |
| Genre | `2D Platformer` |
| Tools | `Unity` |
| Global Game Jam Page | https://v3.globalgamejam.org/2023/games/reforest-revenge-9 |

> [!IMPORTANT]
> The concept, story, and mechanics were developed under the time constraints and creative challenge of a game jam.

---

## Awards

**Reforest Revenge** received the following recognition during the game jam:

| Award | Result |
|---|---|
| Most Creative Project | Winner |
| Global Game Jam | 2nd Place |

> [!NOTE]
> These awards were received as part of the game jam event where **Reforest Revenge** was developed.

---

## Overview

**Reforest Revenge** is a 2D platformer developed in Unity. The game takes place in a future world heavily affected by deforestation. In response to the destruction of nature, Mother Nature creates **Rooty**, a supernatural creature formed from the roots of fallen trees.

Rooty's mission is to reforest the world while facing enemies such as forest engineers and hunters who work for a company that does not care about nature.

The project includes:

- A main menu scene.
- A settings scene.
- A credits scene.
- A playable level scene.
- Player movement and jumping.
- Enemy patrol and collision behavior.
- Health and damage mechanics.
- Collectible water drops.
- Dialog signs.
- Audio and UI settings.

> [!NOTE]
> The game mixes an environmental message with accessible 2D platformer gameplay.

---

## Story

In a not-so-distant future, the world has been almost completely deforested. This destruction angers Mother Nature, who creates a supernatural creature from the roots of cut-down trees.

That creature is named **Rooty**.

Rooty must reforest the forest while driving away the engineers and hunters working for a capitalist company that exploits nature without caring about the consequences.

> [!TIP]
> The theme **"Roots"** is represented both literally, through Rooty's origin, and symbolically, through the game's message about nature, restoration, and environmental responsibility.

---

## Features

- 2D platformer gameplay.
- Player movement and jumping.
- Rooty as the main playable character.
- Enemy interactions.
- Enemy patrol behavior.
- Player health system.
- Collectible water drops.
- Victory zone.
- Death zone.
- Dialog signs.
- Main menu.
- Settings menu.
- Credits screen.
- Audio management.
- Background music.
- Sound effects.
- Brightness setting.
- Volume setting.
- Quality setting.
- Resolution setting.
- Fullscreen toggle.
- Pixel-art inspired visual assets.
- Animated sprites.
- Cinemachine camera support.
- Universal Render Pipeline support.

---

## Project Structure

```text
Reforest-Revenge/
│
├── Assets/
│   ├── Audio/
│   ├── Cainos/
│   ├── Character/
│   ├── Documentation/
│   ├── Environment/
│   ├── Evidencias/
│   ├── Menu Sprites/
│   ├── Mod Assets/
│   ├── Prefabs/
│   ├── Rendering/
│   ├── Scenes/
│   ├── Scripts/
│   ├── Settings/
│   ├── TextMesh Pro/
│   ├── Tiles/
│   ├── TutorialInfo/
│   └── Tutorials/
│
├── Packages/
│   └── manifest.json
│
├── ProjectSettings/
│   └── ProjectVersion.txt
│
├── .gitignore
├── .vsconfig
└── README.md
```

---

## Main Folders

| Folder | Description |
|---|---|
| `Assets/Audio` | Contains music and sound effects used in the game. |
| `Assets/Character` | Contains player and enemy sprites, animations, and character assets. |
| `Assets/Environment` | Contains environment tiles, backgrounds, props, and level art. |
| `Assets/Evidencias` | Contains cover art, screenshots, GIFs, and video evidence of the project. |
| `Assets/Scenes` | Contains the Unity scenes used by the game. |
| `Assets/Scripts` | Contains the C# scripts that control gameplay, UI, audio, and mechanics. |
| `Assets/Prefabs` | Contains reusable Unity objects. |
| `Assets/Settings` | Contains project rendering and configuration assets. |
| `Packages` | Contains Unity package dependencies. |
| `ProjectSettings` | Contains Unity project configuration files. |

---

## Unity Version

This project was made with:

```text
Unity 2021.3.18f1
```

> [!TIP]
> If Unity asks to upgrade the project, make a backup before opening it in a newer Unity version.

---

## Dependencies

The project uses several Unity packages, including:

| Package | Purpose |
|---|---|
| `Cinemachine` | Camera control and smooth camera behavior. |
| `Universal Render Pipeline` | 2D rendering and graphics pipeline. |
| `TextMeshPro` | Improved text rendering for UI. |
| `Unity UI` | Menus, sliders, buttons, and interface elements. |
| `Unity Timeline` | Timeline support. |
| `Unity Visual Scripting` | Visual scripting support. |
| `Unity Test Framework` | Testing support. |
| `2D Feature Set` | 2D game development tools. |

> [!NOTE]
> Unity should automatically install the required packages when the project is opened, based on the `Packages/manifest.json` file.

---

## Scenes

The project includes the following main scenes:

| Scene | Path | Description |
|---|---|---|
| `menu` | `Assets/Scenes/menu.unity` | Main menu scene. |
| `Settings` | `Assets/Scenes/Settings.unity` | Settings screen for audio, brightness, resolution, and quality. |
| `Credits` | `Assets/Scenes/Credits.unity` | Credits scene. |
| `Nivel1` | `Assets/Scenes/Nivel1.unity` | Main playable level. |
| `Test` | `Assets/Scenes/Test.unity` | Test scene included in the project files. |

> [!IMPORTANT]
> The enabled build scenes are `menu`, `Settings`, `Credits`, and `Nivel1`.

---

## Installation

1. Clone the repository:

```text
git clone https://github.com/YOUR-USERNAME/Reforest-Revenge.git
```

2. Open Unity Hub.

3. Click **Add project**.

4. Select the cloned project folder.

5. Open the project using:

```text
Unity 2021.3.18f1
```

6. Wait for Unity to import all assets and packages.

7. Open the main scene:

```text
Assets/Scenes/menu.unity
```

8. Press **Play**.

---

## How to Run

1. Open the project in Unity.
2. Open the `menu` scene.
3. Press the **Play** button.
4. Use the menu to start the game or open settings.
5. Play through `Nivel1`.

> [!TIP]
> Start from the `menu` scene instead of directly opening the level scene. This gives the intended game flow.

---

## Controls

The project uses Unity's default input axes and custom input checks.

| Action | Input |
|---|---|
| Move left/right | `A / D` or `Left Arrow / Right Arrow` |
| Jump | `Space` |
| Attack | `F` |
| Return from UI screens | `Escape` |
| Press start / continue from title screen | Any key |

> [!NOTE]
> Movement and jumping are based on Unity's default `Horizontal` and `Jump` inputs.

---

## Gameplay Mechanics

### Player Movement

The player can move horizontally and jump using a platformer-style movement system.

The player controller handles:

- Horizontal movement.
- Jumping.
- Landing.
- Sprite flipping.
- Animation states.
- Attack input.
- Damage animation.
- Scene transition to credits after the game ends.

---

### Health System

The project includes a health system used by the player and enemies.

Health-related behavior includes:

- Maximum health.
- Current health.
- Incrementing health.
- Decrementing health.
- Triggering death behavior when health reaches zero.

---

### Collectibles

The game includes collectible water drops called `Gotas`.

These items can affect the player's life value when collected.

Collectibles include:

- Idle animation.
- Collected animation.
- Collision detection with the player.
- Life value modification.
- 
---

### Enemies

Enemies include movement and collision behavior.

Enemy mechanics include:

- Patrol path movement.
- Collision with the player.
- Damage to the player.
- Enemy death animation.
- Enemy defeat behavior when attacked or collided with correctly.

---

### Death Zone

The death zone is used to detect when the player falls or enters a dangerous area.

When the player enters a death zone, the game can trigger player death or respawn behavior.

---

### Victory Zone

The victory zone detects when the player reaches the end of the level.

This is used to complete the level and move toward the end-game sequence.

---

### Dialog Signs

The game includes sign interaction logic.

When the player enters the range of a sign:

- A dialog box appears.
- The sign text is displayed.
- Player UI behavior can change while reading the sign.

> [!NOTE]
> Signs are useful for tutorials, story messages, warnings, or level instructions.

---

## UI Systems

The project includes several UI scripts for menus and settings.

### Main Menu

The `Menu` script changes scenes using Unity's `SceneManager`.

This allows buttons to move between:

- Main menu.
- Settings.
- Game level.
- Credits.

---

### Press Start Screen

The `UIPressStart` script detects when the player presses any key.

It then:

- Plays a sound effect.
- Starts a fade animation.
- Hides the title screen.
- Shows the menu screen.

---

### Screen Manager

The `UIScreenManager` script controls UI panels.

It can:

- Enable specific screens.
- Disable screens.
- Play fade animations.
- Close some menus with `Escape`.

---

## Settings

The settings system includes:

| Setting | Description |
|---|---|
| Volume | Controls global audio volume using `AudioListener.volume`. |
| Brightness | Adjusts a brightness panel overlay. |
| Quality | Changes Unity quality level. |
| Resolution | Changes screen resolution. |
| Fullscreen | Toggles fullscreen mode. |

Settings values are saved with Unity's `PlayerPrefs`.

> [!IMPORTANT]
> Because settings use `PlayerPrefs`, saved values can persist between play sessions on the same machine.

---

## Audio

The project includes background music and several sound effects.

Audio files include:

- Collectable sound.
- Death sound.
- Hurt sound.
- Jump sound.
- Landing sounds.
- Walking sounds.
- Background music.
- UI notification sounds.

The project includes audio scripts for:

- Persistent background audio.
- Music playlist playback.
- UI sound effects.
- Global volume control.

---

## Visual Assets

The game uses a 2D visual style with:

- Character sprites.
- Enemy sprites.
- Environmental tiles.
- Forest and platformer assets.
- Menu sprites.
- Backgrounds.
- Animated elements.

---

## Screenshots

<p align="center">
  <img src="Assets/Evidencias/SS4.png" alt="Gameplay Screenshot 3" width="700" />
</p>

<p align="center">
  <img src="Assets/Evidencias/SS.png" alt="Gameplay Screenshot 1" width="700" />
</p>

<p align="center">
  <img src="Assets/Evidencias/SS2.png" alt="Gameplay Screenshot 2" width="700" />
</p>

---

## Scripts Overview

### Core Scripts

| Script | Description |
|---|---|
| `Simulation.cs` | Event-based simulation system used by gameplay events. |
| `HeapQueue.cs` | Queue structure used by the simulation system. |
| `Fuzzy.cs` | Utility methods for approximate value comparisons. |

---

### Gameplay Scripts

| Script | Description |
|---|---|
| `PlayerDeath.cs` | Handles player death events. |
| `PlayerEnemyCollision.cs` | Handles collisions between the player and enemies. |
| `PlayerEnteredDeathZone.cs` | Handles player interaction with death zones. |
| `PlayerEnteredVictoryZone.cs` | Handles player interaction with victory zones. |
| `PlayerJumped.cs` | Handles jump events. |
| `PlayerLanded.cs` | Handles landing events. |
| `PlayerSpawn.cs` | Handles player spawning. |
| `PlayerTokenCollision.cs` | Handles collectible collision behavior. |

---

### Mechanics Scripts

| Script | Description |
|---|---|
| `PlayerController.cs` | Main player movement, jumping, animation, and attack controller. |
| `EnemyController.cs` | Enemy movement, patrol, collision, and death behavior. |
| `Health.cs` | Health and death logic. |
| `Gotas.cs` | Collectible item behavior. |
| `DeathZone.cs` | Detects dangerous areas. |
| `VictoryZone.cs` | Detects level completion. |
| `GameController.cs` | Controls simulation updates and stores the game model. |
| `PatrolPath.cs` | Defines enemy patrol paths. |
| `TokenController.cs` | Animates collectible tokens. |

---

### UI and Menu Scripts

| Script | Description |
|---|---|
| `Menu.cs` | Loads scenes from menu buttons. |
| `UIPressStart.cs` | Handles the title screen start interaction. |
| `UIScreenManager.cs` | Manages UI screens and transitions. |
| `UIAudioManager.cs` | Plays UI sound effects. |
| `SettingVolume.cs` | Controls global volume. |
| `SettingBrightnes.cs` | Controls brightness overlay. |
| `SettingQuality.cs` | Controls graphics quality. |
| `SettingResolution.cs` | Controls screen resolution and fullscreen mode. |

---

## Build Instructions

To build the game:

1. Open the project in Unity.
2. Go to:

```text
File > Build Settings
```

3. Make sure these scenes are included:

```text
Assets/Scenes/menu.unity
Assets/Scenes/Settings.unity
Assets/Scenes/Credits.unity
Assets/Scenes/Nivel1.unity
```

4. Select your target platform.
5. Click **Build**.

> [!IMPORTANT]
> If a scene is missing from Build Settings, scene loading may fail during gameplay.

---

## Team

| Name | Role |
|---|---|
| Christian Raúl Jiménez Hernández | Programmer |
| Luis Ricardo Roldan Rivera | Programmer |
| Rodrigo López Guerra | Lead Programmer |
| Jaime Antonio Aguilera Gómez | Artist |
| Jesus Barragan Sotomayor | Lead Artist |

> [!NOTE]
> The team collaborated on programming, art, gameplay systems, and visual presentation during the game jam.

---

## Credits

This project includes Unity platformer systems, visual assets, audio files, and custom scripts.

### Main project concept:

```text
Reforest Revenge
```

### Development tools:

```text
Unity
C#
TextMeshPro
Cinemachine
Universal Render Pipeline
```

### Global Game Jam page:

```text
https://v3.globalgamejam.org/2023/games/reforest-revenge-9
```

### Audio Credits:

| Asset | Author | Source |
|---|---|---|
| `Mural Legends` | Adriel Fair | Epidemic Sound |

> [!NOTE]
> The background music used in this project is **"Mural Legends"** by **Adriel Fair**, licensed through **Epidemic Sound**.

### Additional Credits

Base Project Reference:

This project used **Diamond Dash** as a baseplate/reference project for the initial Unity structure and gameplay foundation.

| Resource | Creator | Platform | Link |
|---|---|---|---|
| `Diamond Dash` | BoO_RaH_YaN | Unity Play | https://play.unity.com/es/games/6992230e-a5a2-48da-8c2e-65d0381f4dbd/diamond-dash |

> [!NOTE]
> `Diamond Dash` was used as a base/reference resource during development. The final project, **Reforest Revenge**, includes custom gameplay adaptation, visuals, characters, theme, UI, and presentation.

---

## Troubleshooting

### Unity opens the project with errors

Make sure you are using:

```text
Unity 2021.3.18f1
```

or another compatible Unity 2021 LTS version.

> [!WARNING]
> Opening the project in a much newer Unity version may cause package, rendering, or scene compatibility issues.

---

### Missing TextMeshPro assets

If UI text does not display correctly, import TextMeshPro essentials:

```text
Window > TextMeshPro > Import TMP Essential Resources
```

---

### Scene buttons do not work

Check that the target scenes are added to Build Settings.

Required build scenes:

```text
menu
Settings
Credits
Nivel1
```

---

### Audio is too loud or too quiet

Use the settings menu to adjust volume.

The volume setting is controlled globally through:

```text
AudioListener.volume
```

---

### The game starts in the wrong scene

Open this scene first:

```text
Assets/Scenes/menu.unity
```

Then press **Play**.

---

## Possible Improvements

Future versions could include:

- More polished level design.
- More levels.
- Save system.
- Score system.
- Pause menu.
- More enemies.
- Boss fight.
- More collectibles.
- Clearer tutorial messages.
- Improved UI styling.
- Controller support.
- WebGL build.
- Better documentation for assets and credits.
- More environmental storytelling.
- Expanded reforestation mechanics.

---

## Educational Purpose

This project is useful for learning:

- Unity 2D development.
- C# scripting.
- Platformer mechanics.
- Scene management.
- UI menus.
- Audio management.
- PlayerPrefs settings.
- Player movement.
- Enemy behavior.
- Collectible systems.
- Collision detection.
- Animation control.
- Basic game architecture.
- Game jam development workflow.

---

## License

No license has been specified for this project.

If you plan to share, reuse, or publish this project, consider adding a license such as:

- MIT License
- Apache License 2.0
- GNU GPLv3

> [!IMPORTANT]
> Before adding a license, make sure all third-party assets used in the project allow redistribution.

---

## Disclaimer

This game project is intended for educational, portfolio, and game jam purposes.

It is not a commercial-ready release unless the assets, licenses, UI, gameplay balance, and build configuration are fully reviewed.

> [!CAUTION]
> Always verify the licenses of included music, sprites, templates, and third-party assets before publishing the project publicly.
