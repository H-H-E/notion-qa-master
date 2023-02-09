# Electric_Pump

Electric Pump

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

The **Electric Pump** is a powered pump with an internal buffer of 10000mB worth of fluids. It can pump any fluid that is covered in the forge fluid dictionary and can be placed on a shoreline and will pump the fluid under it and anything fluid under it.

## Contents

- 1 Crafting Recipe
- 2 Usage
- 3 Calculations
- 4 Trivia

## Crafting Recipe

|  |  |  |  |  |
| --- | --- | --- | --- | --- |
|  |  |  |  |  |
|  |  |  |  |  |

## Usage

Place the pump 1 block above or adjacent to a source block of any fluid you desire. From then on the pump will collect any source block of the fluid it can find, checking any block it can reach going along all flowing blocks of the liquid. In the end, the pump collects all source blocks originally connected to the block it was placed near. It collects 2000mb/s (100mb/t) of water and 20mb/s (1mb/t) of heavy water for a cost of 100 Jouls per operation (10 Jouls/t).

To collect heavy water, a Filter Upgrade must be installed into the pump.

## Calculations

An operation for the pump is defined as taking in 1 bucket of fluid (10mb of heavy water) every 10 ticks without speed upgrades. The equation for speed upgrades is floor(10*max -x/8), where “max” is the maximum speed multiplier in the config. Below is a table for the default max of 10, along with calculated rates.

Pump Speeds w/ Upgrades | # of upgrades | # of ticks per operation | Calculated Pump Rate (mb/t) | | — | — | — | | 0 | 10 | 100 | | 1 | 7 | 142.9 | | 2 | 5 | 200 | | 3 | 4 | 250 | | 4 | 3 | 333.3 | | 5 | 2 | 500 | | 6 | 1 | 1000 | | 7* | 1 | 1000 | | 8* | 1 | 1000 |

- Due to how the mod calculates tickrate, adding more than 6 speed upgrades is a waste and needlessly uses more power.

## Trivia

- The energy usage displayed is actually per operation, not per tick, so it will actually be less per tick than it shows.

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