# TutorialsMachine_Configuration

**The content of this page is out of date.**
Several interfaces and some information on this page has been changed in recent versions of Mekanism. Mekanism machines have many configuration options, allowing you to design your machine integration and item transportation systems as simple or complex as you need. This guide to Mekanism machine configuration will help you understand the basics of the Mekanism machine graphical user interface (GUI). All the machines operate with the same basic principles, so once you understand “The Mekanism Method” you should be ready to configure any of the Mekanism machines. If, after reading this short tutorial, you still have some questions, please feel free to drop by the Mekanism IRC. (#mekanism on esper.net)

---

## Contents

- 1 The Basic Graphical User Interface (GUI)
- 2 Understanding Slots and Sides
- 3 The Configuration User Interface
- 4 Customizing Your Configuration

## The Basic Graphical User Interface (GUI)

1. Open Input/Output configuration panel. See below for more explanation
2. Power information (mouseover only)
3. Power item input, if using a battery or redstone power source
4. Item input
5. Progress bar / click for recipes
6. Item output
7. Power capacity display
8. Redstone control (disable/high/low)
9. Upgrade input and upgrade information panel (**S**peed & **E**nergy)

## Understanding Slots and Sides

Notice in the GUI above that several of the objects have a colored border. These “**slots**” in the user interface are places where items can be inserted or ejected from the machine. For example, the input (4) is red and the output (6) is dark blue. These are standard input/output colors for Mekanism. You cannot change these colors, but what you **can** change is which side(s) each slot connects to. Yes, you can connect a single slot to multiple sides! For example, you could set the top of the machine to be the input (red), the right side to be an output (blue) and the back to be a second output (blue). In this configuration, if one output slot was blocked, the machine would try to send an item out the second output.

So how do you configure the slots? Read on…

## The Configuration User Interface

The Configuration Panel can be opened from the machine’s GUI. Click the button in the top-left, (1) in the GUI picture, above.

1. Close configuration panel
2. Set input color filters
3. Set output color frame
4. Auto-eject on/off
5. Input filter on/off
6. Slot/side assignment

## Customizing Your Configuration

Everything you need is in the Configuration Panel, pictured above. It may look intimidating at first, but for most installations you will only use a couple controls.

**Common Controls**

- **Auto Eject (4)**. This will tell your machine to automatically eject its output item, if there is a suitable inventory to receive it. If there is nothing to receive an item, the machine will hold onto its products. Mekanism machines will not spill your items all over the floor! :) Clicking the A button will toggle the Auto-Eject function on/off.

Mekanism machine output configuration * **Slot/Side Assignment (6)**. This is where you assign a specific colored slot to the sides of your machine. The image of six squares corresponds to each of the six sides. The gray box in the middle is the front, above that (red) is the top. To the left is the left side (orange), to the right is the right side (dark blue). Below the gray square is the bottom side (green), and in the lower left is the back side (also gray). **Note that all sides are configured as if you were facing the machine**, not from the machines point of view. You can change which slot connects to which side by clicking on the appropriate side. As you click, you will cycle through all available colors. Not all colors will be a valid slot color. So if you wanted to configure your machine like in the example with the top as the input (red) and the right and back sides as outputs (blue), the top and right are already set up, you only need to click the gray box in the lower left a few times until the dark blue color is selected. Done! It really is that easy. Gray is the “no connection” color.

**Advanced Controls** Looking to really customize your system? Read on!

- **Output Color Frame(3)**. This will set a colored “frame” around items as they exit the machine. In the example above, all ejected items will have a green frame. Mekanism Logistics Pipes will use this frame color to route the items to a matching-colored destination. If no destination has a matching color, the first available destination inventory will receive the item.
- **Input Filter on/off(5)**. This turns on/off the input filter feature for the machine. If turned on, then machine will only accept items whose color frames match the input filters. If the colors don’t match the filter… they will not be accepted. You can set the input color filters by using…
- **Input Color Filters(2)**. Like the output configuration (6), each of these squares corresponds with a side of the machine. If a color is set for one of these squares, that side will only accept items if they have a matching color frame. So if you want to be sure that coal goes to the Enrichment Chamber and not the Crusher, set a color filter on the output of the machine that ejects the coal, then set a matching color input filter of your Enrichment Chamber. Magic!

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