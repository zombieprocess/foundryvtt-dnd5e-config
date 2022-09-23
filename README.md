# foundryvtt-dnd5e-config
Version control for the configs we use, and particularly keep track of the modules and their setup

| Organization and layout based on this project:   |
| ------ |
|  https://github.com/jbowensii/FOUNDRYVTT-DnD5e-Base-Game-Configuration |

## Local FoundryVTT directory and file summary

```shell
$ tree -L 2 foundrydata/

foundrydata/
├── Config/
│   ├── license.json
│   └── options.json
├── Data
│   ├── ddb-images/
│   ├── modules/
│   ├── systems/
│   └── worlds/
└── Logs/
    ├── debug.log
    └── error.log

7 directories, 4 files
```

## Modules

### Base Foundry Enhancements
<details>
  <summary>Click to expand</summary

- `Compendium Folders` - organizes Compendium content
- `Changelogs & Conflicts`
- `Dice Tray` - Adds a dice tray
- [`Forien's Copy Environment`](https://foundryvtt.com/packages/forien-copy-environment/) - Export/Import global server configs
- `Foundry Community Macros`
- `lib - Color Settings` - module dependency
- `libWrapper` - module dependency
- `Pings` - longpress mouse button to "ping" a place on a map, shift+click to snap the camera to the location
- `PopOut!` - Pop any window out of the game into it's own dedicated window, great for having notes open
- `Search Anywhere`
- [`Navigation Presets`](https://foundryvtt.com/packages/navigation-presets) - organizes maps, scenes, and chapters/groups
- `Module Compatibility Checker` - See settings > Manage Modules > `Button`
- `Selective Show` - **DO NOT NEED in v10** - function is added into core
- `Settings Extender` - module dependency
- `socketlib` - module dependency
- `Token Mold` - fix and improve token creation from actors with templates
- `Tokenizer` - Edit/Add frames around tokens
</details>

### DnD 5e and Game Automation | Ease of Play
<details>
  <summary>Click to expand</summary>

- `Active Token Effects`
- `Active-Auras`
- `Better Rolls for 5e`
- `Beyond20 companion module`
- `Combat Enhancements`
- `Combat Ready!`
- `Dfreds Convenient Effects`
- `Dfreds Droppables`
- `DNDBeyond Character Sheet for 5E` - Reskin of the default character sheet
- `DNDBeyond NPC Sheet` - Reskin of the default NPC sheet
- `FXMaster`
- `Group Initiative` - Group monster rolls
- `Health Estimate` - Lets people know approximate health
- `Initiative Double Click` - enables fixing Initiative rolls/ordering
- `Item Macro`
- `Automatic Automations` | `Sequencer` | `JB2A` (Tightly coupled)
  - `Dynamic Active Effects SRD`
  - `Dynamic Effects using Active Effects`
- `Let Me Roll that For You` (LMRTFY)
- `MidiQOL` | `Dynamic Active Effects` (DAE) | `Times Up` (Tightly coupled)
  - `Midi SRD`
  - `Token Magic Effects`
- `Mob Attack Tool` - Combine attacks from many creatures into one
- `Perfect Vision` - **MIGHT be going away in v10** because this is in the core
- `Splatter` - blood Splatter on "bloodied"
- [`Trigger Happy`](https://foundryvtt.com/packages/trigger-happy) - Trigger events like pause the game for traps, or descriptions, or make Automations/effects

</details>

### GM Addons to make game prep easier
<details>
  <summary>Click to expand</summary>

  - `Moulinette Core`
    - `Moulinette Game Icons (module)`
    - `Moulinette Image Search (module)`
    - `Moulinette Scenes (module)`
    - `Moulinette Sound & SoundPad (module)`
    - `Moulinette Tiles (module)`

</details>

### Integrations with other tools/sites
<details>
  <summary>Click to expand</summary>

  - [`D&D Beyond Importer`](https://foundryvtt.com/packages/ddb-importer)
  - `The Forge: More Awesomeness` - forge module dependency

</details>

### Evaluating/Testing
<details>
  <summary>Click to expand</summary>

- `Argon - Combat HUD` (active)
- `Combat Carousel` (active)
- `Combat Utility Belt` - (installed but disabled) - might not need it anymore with other automations
- `Dice So Nice!` (installed but disabled)
- `DnD5e UI` (installed but disabled) - Creates nice cards in chat, tab icons change which might require some getting used to
- `Forien's Quest Log` (installed but disabled)
- [`Less Fog`](https://github.com/trdischat/lessfog) (installed but disabled)
- `tabletopaudio` (installed but disabled) - integration with the website https://tabletopaudio.com/ - can create audio streams players can tune in to

</details>

### Future stuff

<details>
  <summary>Click</summary>

- Better Roofs
- Levels
- Wall Height
- Monk's Tokenbar (LMRTFY alternative?)
- DDB Gamelog (DND Beyond)
- Status Icons

</details>
