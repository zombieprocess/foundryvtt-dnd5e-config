# foundryvtt-dnd5e-config
Version control for the configs we use, and particularly keep track of the modules and their setup

## directory and file summary

```shell
$ tree -L 2 foundrydata/

foundrydata/
├── Config
│   ├── license.json
│   └── options.json
├── Data
│   ├── ddb-images
│   ├── modules
│   ├── systems
│   └── worlds
└── Logs
    ├── debug.log
    └── error.log

7 directories, 4 files
```

## Modules

| Notice  |
| ------ |
| Organization and layout based on this project: https://github.com/jbowensii/FOUNDRYVTT-DnD5e-Base-Game-Configuration |

### Base Foundry Enhancements
<details>
  <summary>Click to expand</summary

- `Compendium Folders` - organizes Compendium content
- `Changelogs & Conflicts`
- `Dice Tray` - Adds a dice tray
- `Foundry Community Macros`
- `lib - Color Settings` - module dependency
- `libWrapper` - module dependency
- `Pings` - longpress mouse button to "ping" a place on a map, shift+click to snap the camera to the location
- `PopOut!` - Pop any window out of the game into it's own dedicated window, great for having notes open
- `Search Anywhere`
- [`Navigation Presets`](https://foundryvtt.com/packages/navigation-presets) - organizes maps, scenes, and chapters/groups
- `Module Compatibility Checker`
- `Selective Show`
- `Settings Extender` - module dependency
- `socketlib` - module dependency
- `The Forge: More Awesomeness` - forge module dependency
- `Token Mold` - fix and improve token creation from actors
- `Tokenizer` - Add frames around tokens
</details>

### DnD 5e Game Automation | Ease of Play
<details>
  <summary>DnD 5e Game Automation | Ease of Play</summary>

- `About Time` (pending)
- `Active Token Effects`
- `Active-Auras`
- `Better Rolls for 5e`
- `Beyond20 companion module`
- `Combat Enhancements`
- `Combat Ready!`
- `Combat Utility Belt`
- `Dfreds Convenient Effects`
- `Dfreds Droppables`
- `FXMaster`
- `Group Initiative`
- `Health Estimate`
- `Initiative Double Click`
- `Item Macro`
- `Automatic Automations` | `Sequencer` | `JB2A` (Tightly coupled)
  - `Dynamic Active Effects SRD`
  - `Dynamic Effects using Active Effects`
- `Let Me Roll that For You` (LMRTFY)
- `MidiQOL` | `Dynamic Active Effects` (DAE) | `Times Up` (Tightly coupled)
  - `Midi SRD`
  - `Token Magic Effects`
- `Mob Attack Tool` - Combine attacks from many creatures into one
- `Perfect Vision`
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


</details>

### Evaluating/Testing
<details>
  <summary>Click to expand</summary>

- `Argon - Combat HUD`
- `Combat Carousel`

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
