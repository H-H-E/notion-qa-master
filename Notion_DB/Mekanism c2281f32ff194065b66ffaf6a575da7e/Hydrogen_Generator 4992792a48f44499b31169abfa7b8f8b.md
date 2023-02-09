# Hydrogen_Generator

Gas-Burning Generator

| Mod |  |
| --- | --- |
| Mekanism: Generators |  |
|  |  |
| Type |  |
| Generator |  |
|  |  |
| Tool |  |
|  |  |
|  |  |
| Stackable |  |
| No |  |
|  |  |

A **Gas-Burning Generator** creates power by consuming any burnable gas for example the Hydrogen produced by an Electrolytic Separator or Ethylene. The **Gas-Burning Generator** has its own internal storage tank with a capacity of 18,000 units. Gas Tanks can be used to expand the Hydrogen storage capacity of your system. **Gas-Burning Generators** can generate a maximum of 20,000 J/t (8,000 RF/t). They are an upper tier Mekanism power source that should supply adequate power to your base for a long time, but they are best used when they provide power to charge a bank of Energy Cubes, rather than sending the generator power out directly to your base.

As of 1.7.10, 1.12.2, and 1.16.5, 1 mB of Hydrogen gas is converted to 200 J (80 RF). 1 mB of Ethylene is converted to 28200 J (11280 RF).

A new feature in Mekanism v9 is that the **Gas-Burning Generator** will automatically scale its burning rate according to the amount of power stored in its internal buffer (this is usually determined by the tier of Universal Cable it is attached to). The burning rate will increase until the generator is producing the maximum output of 20,000 J/t (8,000 RF/t). This is 100 mB/t for Hydrogen and 0.7 mB/t for Ethylene. The rate is displayed on the right side of the GUI, below the gas and power storage indicators.

In Mekanism v10 for 1.16.5, the maximum gas burning and power generation rate is increased. Hydrogen is burned at a maximum rate of 256 mB/t, generating up to 20,480 RF/t, and Ethylene is burned at a maximum rate of 6.4 mB/t, generating up to 72,192 RF/t.

## Contents

- 1 Crafting Recipe
- 2 User Interface
- 3 Sample Gas-Burning Generator setup
- 4 Trivia

## Crafting Recipe

|  |  |  |  |  |
| --- | --- | --- | --- | --- |
|  |  |  |  |  |
|  |  |  |  |  |

## User Interface

1. Visual hydrogen storage indicator
2. Gas Tank can be placed here to fill the internal hydrogen tank
3. Energy Info Display: generation level, storage level, maximum power output from the energy buffer
4. Place a chargeable item here to be charged
5. Visual power buffer level
6. Redstone switch setting (high/low/disabled)

## Sample Gas-Burning Generator setup

1. Solar Generators deliver power to an Electric Pump (2) and a Electrolytic Separator (3) via Universal Cable
2. Electric Pump, sitting in a corner of a 3x3 pond, delivers water to the Electrolytic Separator (3) via Mechanical Pipe
3. Electrolytic Separator delivers hydrogen to the Gas-Burning Generator (4) via Pressurized Tube. Set the Separator to dump oxygen, otherwise it will stop when the oxygen tank fills.
4. Gas-Burning Generator consumes the hydrogen and generates power to an Energy Cube (5) via Universal Cable.
5. Energy Cube receives power from the Gas-Burning Generator (4) via Universal Cable.

Notes:

- Each pump in the system can run 10 Electrolytic Separators.
- Each Electrolytic Separators can run one Gas-Burning Generator.

WARNING: This setup will not work in 1.7.10 as the Electrolytic Separator needs 400 joules of power (J/t) to run. The purpose of this change was to turn Hydrogen into an *energy carrier*.

See https://github.com/aidancbrady/Mekanism/issues/1037

## Trivia

- In previous versions of Mekanism it was called **Hydrogen Generator** and used Hydrogen only.

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