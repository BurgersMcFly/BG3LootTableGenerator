# BG3LootTableGenerator
Fork of BG3LootTableGenerator for personal use with some minor changes.

# Differences from the original:
Looks for english.loca.xml instead of english.xml since loca.xml is the default output of BG3 multitool. Adds current date to the dumped .json files (e.g. items_1_20_2024.json)

# Usage
Export game data with [BG3-Modders-Multitool](https://github.com/ShinyHobo/BG3-Modders-Multitool). You need Gustav.pak, Shared.pak and English.pak.

Dump data to .json files with: `BGLootTableGenerator.exe [path_to_unpacked_content] [path_to_output_dir]`, for example: `BGLootTableGenerator.exe "C:\Users\Lia\Desktop\BG3\ModdersMultitool\UnpackedData" "C:\Users\Lia\Desktop\BG3\MyMods\.dev\.generation"`

You'll get:

- `items.json`: every item, formatted in a much more searchable/parseable way
- `levels.json`: every level, formatted in a much more searchable/parseable way
- `traders.json`: every trader, formatted in a much more searchable/parseable way

# Credits
Full credits to [Liareth](https://github.com/Liareth). This is just a fork of their tool [BG3LootTableGenerator](https://github.com/Liareth/BG3LootTableGenerator) with some minor changes for personal usage.
