# Torches

Torches is a datapack for Minecraft: Java Edition that simplifies torch
crafting. The main branch is compatible with Minecraft versions from `1.21.2`
to `1.21.4` inclusive. For other versions see tags, eg. `1.19-1.20.4`.

## About changes to recipes

The normal torch crafting recipe is removed and replaced with several shapeless
recipes, allowing larger amounts of torches be crafted using coal blocks, logs,
planks and sticks. This is to remove tedious "extra steps" of torch crafting,
ie. needing to craft logs into sticks and coal blocks to coal.

*A notable side effect* is that one coal block is now equivalent to eight
pieces of coal instead of the usual nine (since a log can also be crafted into
eight sticks and not nine.) Some other coal-related recipes are also added, [see
below](#new-coal-recipes-shapeless).

## List of new recipes

### New torch recipes (shapeless)

| Wood Ingredients | Coal Ingredients | Result |
| :-- | :-- | :-- |
| Any log or wood block | 1 coal block | 32 torches |
| Any log or wood block | 8 coal or charcoal | 32 torches |
| Any 4 planks | 1 coal block | 32 torches |
| Any plank | 2 coal or charcoal | 8 torches |
| 8 sticks | 1 coal block | 32 torches |
| 1 stick | 1 coal or charcoal | 4 torches |

### New coal recipes (shapeless)

| Ingredient | Result |
| :-- | :-- |
| 1 coal block | 8 coal |
| 8 coal or charcoal | 1 coal block |
| 1 coal | 1 charcoal |
| 1 charcoal | 1 coal |

## Installation

To install the datapack first download the repository as a zip archive. You can
obtain the latest version under Code > Download ZIP. For older versions check
[Releases](https://github.com/safeliquids/torches/releases) and download the zip
under Assets > Source code (zip).

Then extract the zip inside the `datapacks` folder in your world folder. The
result should look something like this.
```
my-world/
  - datapacks/
    - torches-main/
      - data/
      - pack.mcmeta
      - README.md
  - level.dat
  - (... lots of other folders and files)
```
