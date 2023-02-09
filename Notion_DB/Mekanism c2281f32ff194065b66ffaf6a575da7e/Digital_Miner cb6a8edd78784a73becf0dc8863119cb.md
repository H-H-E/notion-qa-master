# Digital_Miner

Digital Miner

| Mod |  |
| --- | --- |
| Mekanism |  |
|  |  |
| Type |  |
| Machine |  |
|  |  |
| Tool |  |
| ? |  |
|  |  |
| Stackable |  |
| N/A |  |
|  |  |

The **Digital Miner** is the scale mining machine of Mekanism. However, this machine is like no other as it “magically-teleports” mined blocks to its inventory.

The player can set the mining radius and the depth for its scanning area. The player can also opt to replace all mined blocks should the player wish to do so by keeping it fed with the desired material. The Digital Miner can be configured to mine ores only within a certain area. The Digital Miner can also be set to silk touch ores, but this results in higher power consumption. Like all other Mekanism machines, the Digital Miner can automatically remove ores from its inventory for automated processing by other machines. It also takes the same upgrades as other Mekanism machines. It is also known that placing a Digital Miner in a claim (claims on servers) will stop it from working.

## Contents

- 1 Crafting Recipe
- 2 Usage
- 3 Main Interface
- 4 Config Interface
- 5 Modes
    - 5.1 Inverse Mode
    - 5.2 Silk Touch Mode
    - 5.3 Auto-Eject
    - 5.4 Auto-Pull
    - 5.5 Block Replacement
- 6 Filters
    - 6.1 ItemStack/Item
    - 6.2 OreDict/Ore Dictionary
    - 6.3 Material
    - 6.4 Mod ID

## Crafting Recipe

Ingredients | Crafting recipe |
— | — |
Steel Casing +

Atomic Alloy + Logistical Sorter + Teleportation Core + Robit + Basic Control Circuit |

|  |  |  |  |  |
| --- | --- | --- | --- | --- |
|  |  |  |  |  |
|  |  |  |  |  |

|

## Usage

To begin, the Digital Miner needs a source of power. It can be powered through its energy slot (see GUI below) or by one of its three energy ports (indicated by a green square), which are situated on the sides and bottom.

In the main interface, click on the gray Config button to specify the area and filters for him to use. If you do not wish to leave empty spaces where ore blocks used to be, fill the block replacement slot with any block, turn on the requirement in the filters, and supply the necessary blocks in the machine’s inventory.

Once powered and your filters made, hit the Start button back in the main interface to start mining.

The Digital Miner has two IO-Slots (indicated by a yellowish-tan square), the one on the back, where the items can be picked up, i.e. by Logistical Transporter (mod equivalent of an item pipe) and the one on the top front to insert replacement blocks, i.e. from a bin (mod equivalent of a container).

To speed up the miner, use speed upgrades. To increase the energy capacity and efficiency of the miner, install energy upgrades. Up to 8 can be used for a 10x effect for both upgrades.

It is not recommended to use the digital miner to break items of high importance (machinery/altars) without first testing what effects it can cause (worst case being the item breaks without it dropping and not appearing in the Digital Miner’s inventory). If you are unsure of anything, try testing the desired item/block first (ores should always be safe to mine).

Even though it can bypass obstacles (e.g. warded zones from Thaumcraft, shielded areas from RFTools etc.) by directly accessing the block, it cannot break unharvestable blocks or redstone.

For more detailed information, read the sections below.

## Main Interface

Number | Label | Description |
— | — | — |
1 | Start Button | Initiates mining. Upon running for the first time after being placed or reset, it will scan the area for the desired blocks. It will NOT scan the area for any blocks/items placed after the start button was pressed. The miner will need to be reset for it to re-scan the area for new blocks. |
2 | Stop Button | Stops mining. |
3 | Config Button | Brings up the config interface (see GUI below). This button will be unavailable to click once the start button has been pressed, the reset button must be pressed to allow access to the config interface. |
4 | Energy Slot | Insert a source of energy (like a charged Energy Tablet or Energy Cube) to power the digital miner. This does not need to be used if power is provided externally through one of its energy ports. |
5 | Block Status | Indicates if blocks are needed to replace mined ones. If the indication is on, you will need to supply the shown block or else the miner will not continue to mine. |
6 | Reset Button | Resets the digital miner; allows for the config to be accessed again and re-scans the area for new blocks after hitting the start button. |
7 | Auto-Eject Button | Toggles auto-eject mode; automatically ejects blocks/items not used for replacing mined ones. If there is nothing connected to the output port, the miner will not eject anything. |
8 | Silk Touch Button | Toggles Silk Touch mode, where mined blocks act as if mined by a pickaxe enchanted with silk touch. This mode comes at the expense of utilizing six times as much energy. |
9 | Auto-Pull Button | Toggles auto-pull mode; automatically pulls blocks from a container (like a bin) for replacing mined blocks. Do not insert items in the top port (like a pipe or an export bus), just place the container (with the corresponding blocks) directly on top of the port. |
10 | Upgrade Tab | Opens up the upgrade interface. The digital miner is able to accept speed and energy upgrades, eight each for a maximum multiplier effect of 10. |
11 | Security Tab | Changes who is allowed to use/access the digital miner. Set it to private to restrict other players, public for free access, or trusted for friends. |
12 | Redstone Control | Changes the behavior of the digital miner with redstone. Default setting is disabled, allowing for manual control. The digital miner can accept the signal on any of its sides. |
13 | Energy Information | Indicates how much energy will be utilized during operation, how much is needed if lacking an insufficient supply of energy and the current unit of energy. Click this tab to change the energy unit used (RF/EU/MJ/J). |
14 | Visual Toggle | Click this to see the area that the digital miner will cover when mining. The visuals/field will appear as white cubes so as long as the area is not occupied by any blocks. The white cubes represent the maximum area the digital miner will cover, including blocks at those cubes. |
15 | Display Screen | Displays the current status of the digital miner. ‘Idle’ when not running, ‘Running’ when operating, ‘Not Ready’ when machine has not run after being reset, ‘Ready’ after running at least once, what modes are currently active (On/Off) and how many blocks are left to be mined. |
16 | Energy Buffer | Hover the cursor over the bar to see how much energy is currently stored by the digital miner. As it depletes, the green bar will decrease. |
17 | Digital Miner Inventory | Mined blocks/items will be stored here. Replacement blocks for the mined blocks can also be placed here instead of using a container with blocks and auto-pull mode active. Once this inventory is full, the digital miner will continue to run but not mine any blocks, so please ensure that this inventory is kept cleared by collecting the items or by using the auto-eject function. |

## Config Interface

Number | Label | Description |
— | — | — |
1 | Back Arrow | This arrow brings you back to the main interface. |
2 | Scroll Bar | If you have more than four filters, drag the slider to view the other filters. Alternatively you can just use your mousewheel. |
3 | Filter List | Edit/Delete your filters by clicking them. You can adjust the priority of what is mined first or last by clicking the triangular arrows near the bottom right corner of each filter (top is highest, bottom is lowest). Sadly you CANNOT turn a filter on/off. |
4 | Create New Filter Button | Click this to add a new filter for the digital miner to use. You can choose between ‘ItemStack’, ‘OreDict’, ‘Material’, and ‘Mod ID’. Once you’ve chosen one, you’ll have to configure it (see Filters below for more info). |
5 | Inverse Button | Toggles inverse mode, in which it will mine everything but the blocks/items listed in the filter list. A practical use for this is to add filters for common blocks like stone, gravel, dirt, grass, sand, etc., using inverse mode this way will make it mine everything, even blocks that might not be included in the ore dictionary. |
6 | Config Screen | Displays the current amount of filters made/used (after the T colon), the radius (in blocks), the minimum y-value, the maximum y-value, the last three contributing to what area the digital miner will cover, and lastly whether inverse mode is on or off (after the I colon). |
7 | Radius Setting | Type in the radius you want the digital miner to cover in the black text box left to the check box. Acceptable values are 0-32, where 0 is one block directly at the center of the digital miner, 1-32 will add the corresponding sized square around this block (# of blocks from the center to the edge/corner). Area: (2x+1)2, x = radius. |
8 | Minimum Y-value Setting | Type in the minimum y-value the digital miner will cover. This value cannot be higher than the maximum y-value, if set to a higher value, it will be set to the current maximum y-value. Setting the max/min y-values to the same number allows the miner to mine one layer of blocks. |
9 | Maximum Y-value Setting | Type in the maximum y-value the digital miner will cover. This value cannot be lower than the minimum y-value, if set to a lower value, the value will not change from its current one. |

## Modes

### Inverse Mode

The “I” icon toggle Inverse mode. Inverse mode mines everything that is not in the in the list. A practial use for this is to put Dirt, Grass, Sand, Sandstone, Gravel, Cobblestone and Stone into the ItemStack list and toggle the Inverse mode. The Digital Miner will mine everything **but** these common materials.

### Silk Touch Mode

The Silk Touch button toggles the Silk Touch mode. When mining coal, the miner will instead receive Coal Ore blocks, rather than pieces of Coal. However, this mode requires 6x the amount of energy it needs.

### Auto-Eject

The Auto-Eject button toggles the eject function. When a block is mined, the block will automatically be sent to a connected pipe, leading to a chest or to an ore processing machine. If the other end of the pipe is not attached to anything, the miner won’t eject them.

### Auto-Pull

The Auto-Pull button toggles the pull function. When a block is mined, the miner will automatically collect one block from a container to replace the mined block. If the required replacement block is missing from the container, depending on the state of the block replacement requirement setting is (active for any filter or inactive for all filters), the miner will stop (active) or continue mining (inactive).

### Block Replacement

Not really a mode, but a feature of the filters. When a block is mined, you can choose to leave another block in its it by specifying a block in the filter. Using Auto-Pull mode with this feature is highly recommended so as to keep the digital miner inventory clear and not having to frequently worry about keeping a constant flow/supply of replacement blocks.

## Filters

### ItemStack/Item

**Description**: This filter allows you to mine/break items (that you can place down) and blocks that you currently have in your possession. Some items (e.g. string) cannot be added to the filter despite being able to be placed in the world. If nothing is being detected (it says 0 below the “To mine:” in the display screen of the main interface) when you start to mine, try turning fuzzy mode on (this will likely be the case for items that can have different orientations, e.g. levers and buttons).

Number | Label | Description |
— | — | — |
1 | Back Arrow | Brings you back to the Create New Filter screen. |
2 | Item Slot | Put the item/block you desire to mine/break here. It’ll just remember what item you put there, the item/block you used is still available to you. |
3 | Fuzzy Mode | Toggles fuzzy mode, in which the filter will also include all metadata values for the id of the item/block. Hover over this to see if fuzzy mode is off or on. |
4 | Save Button | Saves your game…no, it’ll just add the filter to the miner or save any changes you made to the filter. |
5 | Delete Button | Deletes the filter. What more could you want? (Allow redstone maybe?) |
6 | Require Replacement Setting | Turn this on to force the miner to only mine so as long as the block/item in the replacement slot is in the digital miner’s inventory or in a container on the import port with auto-pull mode activated. It’ll inform you what blocks are missing in the block status on the main interface while mining. |
7 | Replacement Slot | Put the block item or block you want to be put in place of the item/block you’re mining. |
8 | Filter Display Screen | Nothing too noteworthy, just make sure what you read is what you wanted to do. |

**Suggested Uses**:

- Avoid trolling/griefing by setting it to TNT or hidden pressure plates to disable traps. Found a non-destructive troll? Rewire it nearby and make the unsuspecting sap responsible trip it off while he/she’s checking what happened (just make sure not to reset the miner and turn it on, you’ll undo “your” handiwork).
- Set it to Essence Oreberry bush (Tinkers’ Construct) and turn fuzzy mode on to find bushes without having to manually search for them for an experience farm.
- Got a bunch of multi-colored wool/clay that you want to remove but can’t vein-mine? Set it to wool/clay and turn fuzzy mode on and go do something else while you wait.
- Change parts of your house from one block (put it in the Item Slot) to another (put it in the Replacement Slot) to swap them with minimal effort.
- Warded blocks around your chest or ME drive (AE2)? Set it a chest or ME drive and turn fuzzy mode on and grab your stuff through the blocks. Only do this if you’re sure you can get them or you’ll risk despawning them. A single block on each side should be fine (test first).

### OreDict/Ore Dictionary

**Description**: This filter allows you to mine ores or blocks by using their ore dictionary names. Depending on what mods you’ve got, you may be able to see the name by holding shift while hovering over the ore/block you want to mine (can be done in NEI), if not you’ll have to use a Dictionary. After entering the name and hitting the checkbox, you’ll see the icon of the ore/block in the slot in the ore slot if it worked, otherwise, you’ll see a blank slot. This means the name doesn’t exist or you didn’t spell and/or capitalize the name correctly. It should also be noted that `*` can be used, when added at the end, it mines everything starting with the given name, e.g. `oreC*` will mine coal ore (oreCoal), copper ore (oreCopper) and certus quartz ore (oreCertusQuartz and oreChargedCertusQuartz).

Number | Label | Description |
— | — | — |
1 | Back Arrow | Brings you back to the Create New Filter screen. |
2 | Ore Slot | The ores/blocks with the matching ore dictionary name entered will appear here, shifting from one to the next. If there is nothing displayed then the name is invalid (unless the ore is invisible). |
3 | Ore Dictionary Input Box | Type the ore dictionary name here and click the little checkbox to the right or hit the enter key to input the name. |
4 | Save Button | Saves your game…no, it’ll just add the filter to the miner or save any changes you made to the filter. |
5 | Delete Button | Deletes the filter. What more could you want? (The ability to turn on/off a filter maybe?) |
6 | Require Replacement Setting | Turn this on to force the miner to only mine so as long as the block/item in the replacement slot is in the digital miner’s inventory or in a container on the import port with auto-pull mode activated. It’ll inform you what blocks are missing in the block status on the main interface while mining. |
7 | Replacement Slot | Put the block item or block you want to be put in place of the item/block you’re mining. |
8 | Filter Display Screen | Nothing too noteworthy, you’ll see the name (key) that you inputted (if you did). |

**Example codes**:

- To mine Gold Ore: `oreGold`
- To mine Redstone (redstone ore in Silk Touch mode): `oreRedstone`
- To mine everything that is made out of wood: `Wood`
- To mine Obsidian: `blockObsidian`
- To mine every ore: `ore*`
- To mine whatever is made out of Emerald (Emerald block, Emerald ore): `Emerald`

### Material

**Description**: This filter allows you to mine blocks made out of a certain material. The detection is not perfected yet as it may miss some blocks even though it can be crafted by the material specified, other times it will mine similar material even though it’s not made out of the material specified, e.g. specify oak wood planks, it will mine spruce stairs. Similar to the ItemStack/Item filter, not all items and blocks will be accepted, even diamonds cannot be specified despite being used in a wide variety of blocks/machines.

Number | Label | Description |
— | — | — |
1 | Back Arrow | Brings you back to the Create New Filter screen. |
2 | Material Slot | Put the material (block/item) you wish to mine/break here. Common materials (like redstone, diamonds, dusts, gears, etc.) cannot be placed here (likely a bug/oversight). |
3 | Filter Display Screen | Nothing too noteworthy, you’ll see the name of the material you put in (if it was valid). |
4 | Save Button | Saves your game…no, it’ll just add the filter to the miner or save any changes you made to the filter. |
5 | Delete Button | Deletes the filter. What more could you want? (A more functional material filter maybe?) |
6 | Require Replacement Setting | Turn this on to force the miner to only mine so as long as the block/item in the replacement slot is in the digital miner’s inventory or in a container on the import port with auto-pull mode activated. It’ll inform you what blocks are missing in the block status on the main interface while mining. |
7 | Replacement Slot | Put the block item or block you want to be put in place of the item/block you’re mining. |

**Unlikely Use**:

- In case you were put in an evil modpack with common materials (wood and cobblestone) only being harvestable by uncrafting them and this same modpack somehow has Mekanism, set the desired material and harvest away while you think about what Minecraftian life choices you made led you here. (In other words, the previous two filters should meet your needs.)

### Mod ID

**Description**: This filter allows you to mine blocks/items by mod ID. Although you can find out what the mod ID in game is by pressing **F3 + h** simultaneously, it doesn’t seem as if Mekanism uses these IDs (save for Mekanism core). There seems to be an established list of mods that Mekanism uses, most well-known mods (e.g. Ender IO) should be available to enter. Not all blocks/items will be mined even though the item couldn’t be added to ItemStack/Item filter but is in the mod (e.g. entering the ID: `Minecraft` will still not allow the miner to detect/mine redstone repeaters and comparators). Like with the OreDict filter, `*` can also be used at the end to set the filter to use any mod IDs beginning what was before the asterisk (e.g. inputting `Thermal*` will use the IDs: Thermal Foundation and Thermal Expansion. After entering the ID and hitting the checkbox, you’ll see various blocks from the specified mod in the mod slot if it worked, otherwise, you’ll see a blank slot.

Number | Label | Description |
— | — | — |
1 | Back Arrow | Brings you back to the Create New Filter screen. |
2 | Mod Slot | Various blocks from the specified mod will appear here, shifting from one to the next. If there is nothing displayed then the name is invalid. |
3 | Mod ID Input Box | Type the mod ID here and click the little checkbox to the right or hit the enter key to input the name. |
4 | Save Button | Saves your game…no, it’ll just add the filter to the miner or save any changes you made to the filter. |
5 | Delete Button | Deletes the filter. What more could you want? (More usable IDs maybe?) |
6 | Require Replacement Setting | Turn this on to force the miner to only mine so as long as the block/item in the replacement slot is in the digital miner’s inventory or in a container on the import port with auto-pull mode activated. It’ll inform you what blocks are missing in the block status on the main interface while mining. |
7 | Replacement Slot | Put the block item or block you want to be put in place of the item/block you’re mining. |
8 | Filter Display Screen | Nothing too noteworthy, you’ll see the mod ID (if you inputted one). |

**Recognized Mod IDs**:

- Applied Energistics 2
- Chisel
- Ender IO
- Minecraft
- Mekanism
- Tinkers* (You cannot type apostrophes in the Input box)
- Thermal Foundation
- Thermal Expansion
- Natura
- *Add more*

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