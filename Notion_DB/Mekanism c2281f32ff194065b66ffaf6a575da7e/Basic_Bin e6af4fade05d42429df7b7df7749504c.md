# Basic_Bin

Bins

| Mod |  |
| --- | --- |
| Mekanism |  |
|  |  |
| Type |  |
| Storage |  |
|  |  |
| Capacity |  |
| Basic: 4,096 Items |  |

Advanced: 8,192 Items Elite: 32,768 Items Ultimate: 262,144 Items Creative: 2,147,483,647 Items | | Tool | | | Stackable | No |

**Bins** are storage blocks that can store a large quantity of a single item; the amount of which depends on its tier. It will retain its inventory when broken with a pickaxe or removed using a Configurator.

## Contents

- 1 Obtaining
    - 1.1 Breaking
    - 1.2 Crafting
- 2 Usage
    - 2.1 Portable Inventory
    - 2.2 Comparator Interaction
    - 2.3 Automation
    - 2.4 Upgrading Tier
    - 2.5 Light Source
- 3 Statistics and Information
- 4 Block Data
    - 4.1 Block States
    - 4.2 NBT Data
- 5 Gallery
- 6 References

## Obtaining

### Breaking

Bins require a pickaxe of any type to be mined or the use of a Configurator in wrench mode. Breaking a bin without using a pickaxe will result in the loss of all items that were inside of it.

### Crafting

Bins are crafting using five cobblestone, one control circuit of the corresponding tier, one bin of the previous tier (if applicable), and two of either redstone dust or a type of alloy depending on the bin’s tier. Any item with the tag “*forge:cobblestone*” can be substituted for vanilla cobblestone in the recipe. Note that blackstone can not be used for crafting bins, as it does not have the aforementioned tag.

Name | Ingredients | Crafting recipe |
— | — | — |
Basic Bin | Redstone +

Cobblestone + Basic Control Circuit |

|  |  |  |  |  |
| --- | --- | --- | --- | --- |
|  |  |  |  |  |
|  |  |  |  |  |

| | Advanced Bin | Infused Alloy + Cobblestone + Advanced Control Circuit + Basic Bin |

|  |  |  |  |  |
| --- | --- | --- | --- | --- |
|  |  |  |  |  |
|  |  |  |  |  |

| | Elite Bin | Reinforced Alloy + Cobblestone + Elite Control Circuit + Advanced Bin |

|  |  |  |  |  |
| --- | --- | --- | --- | --- |
|  |  |  |  |  |
|  |  |  |  |  |

| | Ultimate Bin | Atomic Alloy + Cobblestone + Ultimate Control Circuit + Elite Bin |

|  |  |  |  |  |
| --- | --- | --- | --- | --- |
|  |  |  |  |  |
|  |  |  |  |  |

|

## Usage

An Ultimate Bin containing 192 Cobblestone Bins have a single storage slot that ignores normal item stacking limits, allowing a large amount of a single type of item to be stored in them. However, bins do not bypass the requirement for every item in the stack to share the same NBT data. As a result, renamed, enchanted, or damaged items can not be stacked in the bin; nor can shulker boxes, backpacks, tanks, or any other portable inventory be stacked, regardless of being vanilla or from a mod. This also includes tools that can be charged with RF or any other fluid, such as the jetpack, flamethrower, or the Configurator.

To insert items, right-click any side of the bin while holding the item in the main hand. Note that the amount currently in the player’s hand is the amount that will be inserted. Double right-clicking the bin with the item in hand will deposit all of the items of the same type in the player’s inventory into the bin. Left-clicking on the front (the side with the item icon and the amount of items displayed as a number) will extract one stack of items, while shift left-clicking will extract exactly one item.

### Portable Inventory

As bins retain their inventory when picked up, they can be used as portable item storage, similar to how shulker boxes act in vanilla. Unlike shulker boxes, bins permit items to be both inserted and extracted without needing to place it down in the world.

To insert items, the bin can be placed into a crafting grid along with the items the player desires to add, and then removing the bin from the output slot, as long as the items to be inserted are the same as what is already in the bin. To extract items, the bin can be placed in a crafting grid with no other items; from there items can be extracted one stack at a time from the output slot.

### Comparator Interaction

Minimum Items for Output Strength[1] | Bin Type | Basic | Advanced | Elite | Ultimate | Creative | | — | — | — | — | — | — | | Capacity | 4096 | 8192 | 32,768 | 262,144 | Infinite | | Output Strength | Number of Items | | 0 | 0 | 0 | 0 | 0 | 0 | | 1 | 1 | 1 | 1 | 1 | - | | 2 | 293 | 586 | 2341 | 18,725 | - | | 3 | 586 | 1171 | 4682 | 37,450 | - | | 4 | 878 | 1756 | 7022 | 56,174 | - | | 5 | 1171 | 2341 | 9363 | 74,899 | - | | 6 | 1463 | 2926 | 11,703 | 93,623 | - | | 7 | 1756 | 3511 | 14,044 | 112,348 | - | | 8 | 2048 | 4096 | 16,384 | 131,072 | - | | 9 | 2341 | 4682 | 18,725 | 149,797 | - | | 10 | 2634 | 5267 | 21,066 | 168,522 | - | | 11 | 2926 | 5852 | 23,406 | 187,246 | - | | 12 | 3219 | 6437 | 25,747 | 205,971 | - | | 13 | 3511 | 7022 | 28,087 | 224,695 | - | | 14 | 3804 | 7607 | 30,428 | 243,420 | - | | 15 | 4096 | 8192 | 32,768 | 262,144 | Infinite |

The amount of items inside of a bin can be measured using a redstone comparator. The amount of items needed for a given signal strength varies based on the tier, with the exact values being listed in the table on the right. Note that in the case of the creative bin, either 0 or 15 will be outputted depending on whether or not there is an item in the bin, as the creative bin contains an infinite amount of the given item.

### Automation

Items can be inserted and extracted from any side of the bin using hoppers, logistical transporters, or any item pipe from another mod.

By shift right-clicking a bin with a Configurator set to any Configurate mode, auto-output can be toggled. When enabled, items will automatically be ejected one stack at a time into any inventory on the bottom of the bin, assuming that the destination can accept the item. It will not dump items as entities into the world in the event that the block below is not a suitable inventory. A bin will glow when auto-output is enabled, with the colored portions of the sprite being brighter and the block emitting light.

### Upgrading Tier

Similar to machines, bins can be upgraded through the use of tier installers. By holding the installer in the main hand and shift right-clicking the bin, the current bin will be replaced with the next tier of bin while keeping its current inventory. Note that tiers can not be skipped, i.e. the advanced tier installer must be used before the elite installer and the elite tier installer before the ultimate installer.

It is also possible to upgrade a bin by using it in place of an empty bin in the crafting recipe for the next tier of bin. This will not result in the loss of the contents of the bin used in the upgrade.

It is arguably more resource efficient to upgrade bins through the crafting method rather than by using a tier installer. Tier installers require two control circuits, four tier-appropriate alloys, and two ore products; whereas crafting a bin only requires one control circuit and two tier-appropriate alloys.[2]

### Light Source

When auto-output is enabled, bins give off a light level of 15, the maximum permitted by the lighting engine.

## Statistics and Information

| Type | Color | Capacity | Appearance |
| --- | --- | --- | --- |
| Basic Bin | Green |  |  |
| 4,096 Items |  |  |  |
|  |  |  |  |
| Advanced Bin | Red |  |  |
| 8,192 Items |  |  |  |
|  |  |  |  |
| Elite Bin | Blue |  |  |
| 32,768 Items |  |  |  |
|  |  |  |  |
| Ultimate Bin | Purple |  |  |
| 262,144 Items |  |  |  |
|  |  |  |  |
| Creative Bin | Black |  |  |
| Infinite Items (Stored as 2,147,483,647) |  |  |  |
|  |  |  |  |

**Note:** Max capacity and output rate and both configurable in the Config file. By default, the auto-output rate is 3 stacks per second.

## Block Data

### Block States

Name | Default Value | Allowed Values | Description |
— | — | — | — |
active | false | falsetrue | Whether or not auto-output is enabled on the bin. |
facing | north | northeastsouthwest | The direction the bin’s front face (item and amount display) is facing.Opposite the direction the player is facing when the bin is placed. |

### NBT Data

*Root Tag (Compound)*[3]

- **currentRedstone (int)**: The strength of the redstone signal emitted when the block is read by a comparator.
- **updateDelay (int)**: Stores the time before the game will update the auto-output state (block state) again. Starts at 60 and ticks down by 1 every tick.
- **activeState (byte)**: 1 or 0 (true/false). When true, auto-output will be enabled; when false, it is disabled. If altered through commands, *updateDelay* must be greater than 0 in order for the block to reflect the change.
- **x (int)**: The x-coordinate of the block.
- **y (int)**: The y-coordinate of the block.
- **z (int)**: The z-coordinate of the block.
- **Items (List)**: A list of every slot in the container. Will only ever have one entry, as bins only have one slot.
    - ***unnamed* (Compound)**: The single slot of the bin. Contains the item along with the amount stored.
        - **Item (Compound)**: Contains the item ID, amount of the item, and any NBT data the item had.
            - **id (String)**: The namespaced ID of the item or block being stored.
            - **Count (byte)**: Number of items stacked in this inventory slot. If set to 0, the *Items* list will be emptied. While technically having a range from -128 to 127 inclusive, this tag is not used to represent the amount of items beyond 64, instead the *SizeOverride* tag is used.
            - **tag (Compound)**: Optional. Stores additional NBT data of the item, such as enchantments, durability, or custom naming. Supports user-defined tags.
        - **Slot (byte)**: The inventory slot the item is in. Will always be 0.
        - **SizeOverride (int)**: The number of items stacked in the slot. Used when the item count exceeds 64.
- **id (String)**: The namespaced ID of the block.
- **redstone (byte)**: Unknown. The tag does not update when a comparator is attached, when the block is full, when auto-output is enabled or disabled, or when receiving a redstone signal, so it is unclear what the purpose of this tag is.

## Gallery

- The four survival-obtainable bins.

## References

1. ↑ Data obtained through in-game testing on version 10.0.21.
2. ↑ As of version 10.0.21 (latest at time of writing).
3. ↑ NBT format obtained through in-game testing, hidden and optional tags could be missing.

|  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
- v
- t
- e Mekanism | | — | | | | Guides |
- Ore Processing
- Getting Started
- Basic Ore Processing Setup
- Advanced Ore Processing Setup
- Installation Instructions
- Machine Configuration
- Upgrading to Mekanism v8

| | | | Machinery | * Metallurgic Infuser * Enrichment Chamber * Osmium Compressor * Crusher * Combiner * Energized Smelter * Purification Chamber * Digital Miner * Electrolytic Separator * Factory * Precision Sawmill * Pressurized Reaction Chamber * Chemical Injection Chamber * Chemical Infuser * Chemical Oxidizer * Chemical Dissolution Chamber * Chemical Washer * Chemical Crystallizer * Rotary Condensentrator * Seismic Vibrator * Fluidic Plenisher * Solar Neutron Activator * Oredictionificator

| | | | Generators | * Heat Generator * Solar Generator * Advanced Solar Generator * Wind Generator * Bio-Generator * Gas-Burning Generator

| | | | Tools | * Lapis Lazuli Tools * Bronze Tools * Osmium Tools * Glowstone Tools * Steel Tools * Obsidian Tools * Paxel * Gauge Dropper

| | | | Armor | * Lapis Lazuli Armor * Bronze Armor * Osmium Armor * Glowstone Armor * Steel Armor * Obsidian Armor

| | | | Equipment | * Jetpack * Armored Jetpack * Scuba Tank * Gas Mask * Free Runners * Flamethrower

| | | | Ore Processing |

| Ores |  |
| --- | --- |
- Copper Ore
- Tin Ore
- Osmium Ore
- Salt Block
- Uranium Ore

| | | | Dusts | * Dusts * Dirty Dusts * Clumps * Shards * Crystals * Slurry * Enriched Iron

| | | | Ingots | * Copper Ingot * Tin Ingot * Osmium Ingot * Bronze Ingot * Steel Ingot * Obsidian Ingot * Glowstone Ingot

| | | | Compressed | * Compressed Carbon * Compressed Diamond * Compressed Obsidian * Compressed Redstone

|

| | | | Upgrades | * Speed Upgrade * Energy Upgrade * Gas Upgrade * Filter Upgrade * Anchor Upgrade * Factory Installers

| | | | Gadgets | * Atomic Disassembler * Cardboard Box * Chargepad * Configurator * Dictionary * Electric Bow * Electric Pump * Energy Tablet * Portable Teleporter * Robit * Walkie-Talkie * Filter Card * Seismic Reader

| | | | Transmitters | * Logistical Transporter * Restrictive Transporter * Diversion Transporter * Logistical Sorter * Mechanical Pipe * Pressurized Tube * Universal Cable * Thermodynamic Conductor

| | | | Storage |

| Bins |  |
| --- | --- |
- Basic Bin
- Advanced Bin
- Elite Bin
- Ultimate Bin

| | | | Energy Cubes | * Basic Energy Cube * Advanced Energy Cube * Elite Energy Cube * Ultimate Energy Cube

| | | | Gas Tanks | * Basic Gas Tank * Advanced Gas Tank * Elite Gas Tank * Ultimate Gas Tank

| | | | Fluid Tanks | * Basic Fluid Tank * Advanced Fluid Tank * Elite Fluid Tank * Ultimate Fluid Tank

| | | | Multiblock Storage | * Dynamic Tank

| | | | Small Storage | * Personal Chest

|

| | | | Aesthetic Blocks | * Bronze Block * Charcoal Block * Copper Block * Osmium Block * Refined Glowstone * Refined Obsidian * Steel Block * Tin Block * Plastic Block * Glow Panel

| | | | Components | * Solar Panel * Steel Casing * HDPE Pellet * HDPE Sheet * HDPE Rod * PlaStick

| Alloys |  |
| --- | --- |
- Enriched Alloy
- Reinforced Alloy
- Atomic Alloy

| | | | Control Circuits | * Basic Control Circuit * Advanced Control Circuit * Elite Control Circuit * Ultimate Control Circuit

| | | | Cores | * Electrolytic Core * Teleportation Core

| | | | Thermal Evaporation Plant | * Thermal Evaporation Block * Thermal Evaporation Controller * Thermal Evaporation Valve

| | | | Dynamic Tank | * Dynamic Glass * Dynamic Tank * Dynamic Valve

| | | | Teleporter Portal | * Teleporter * Teleporter Frame

| | | | Fusion Reactor | * Reactor Frame * Reactor Port * Reactor Controller * Reactor Glass * Reactor Logic Adapter * Laser Focus Matrix

| | | | Industrial Turbine | * Turbine Casing * Turbine Valve * Turbine Vent * Pressure Disperser * Turbine Blades * Turbine Rotor * Rotational Complex * Electromagnetic Coil * Structural Glass

| | | | Induction Matrix | * Induction Casing * Induction Port * Induction Cells * Induction Providers

| | | | Lasers | * Laser * Laser Amplifier * Laser Tractor Beam

|

| | | | Miscellaneous | * Balloon * Bio Fuel * Gases * MekaCape * Obsidian TNT * Teleporter Portal

|

|