# compendium-folders module config

## export and transformations

1. Navigate to Game settings > Configure Settings > Module Settings > Compendium Folders
2. Press the button `⚙ Import/Export Folder Configuration`
3. Press `Copy to Clipboard` button
4. Paste into a file with your editor

If you want to transform to human legible:
```shell
cat modules/compendium-folders/compendium-folders.json | python3 -m json.tool
```
```json
{
    "hidden": {
        "compendiumList": [],
        "titleText": "hidden-compendiums",
        "_id": "hidden",
        "compendiums": [],
        "expanded": false
    },
    "default": {
        "compendiumList": [],
        "titleText": "Default",
        "_id": "default",
        "colorText": "#000000",
        "compendiums": [],
        "expanded": false
    }
}
```
Sample formatted `json` output
