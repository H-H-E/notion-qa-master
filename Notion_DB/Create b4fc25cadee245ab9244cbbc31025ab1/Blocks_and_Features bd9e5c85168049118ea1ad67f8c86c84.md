# Blocks_and_Features

**Welcome to the Create wiki! Here you will find out about all the details on the features of this mod.**

If you want to navigate the specific blocks and items of create continue to: Create Blocks and Items

If we haven’t gotten around to document what you were looking for, consult the following:

- The Mod JEI for showing the recipes and recipe types added in Create
- The in-game tooltips of Create for description of the individual blocks and items
- For Additional feedback and help please see our Discord

## Contents

- 1 Mod spotlights
- 2 Core Features
    - 2.1 **The Basics of Rotation**
    - 2.2 **Generating and Transferring Rotational Force**
    - 2.3 **Changing Gears**
    - 2.4 Cogwheels
    - 2.5 Adjustable Chain Gearshift
    - 2.6 Rotation Speed Controller
    - 2.7 Overpowering
    - 2.8 **Stress Units**
    - 2.9 **Materials**
    - 2.10 Other Materials
    - 2.11 **Moving Contraptions**
- 3 Contraption Controllers
    - 3.1 Mechanical Piston
    - 3.2 Rope Pulley
    - 3.3 Mechanical Bearing
    - 3.4 Clockwork Bearing
    - 3.5 Cart Assembler
        - 3.5.1 Single Cart Contraptions
        - 3.5.2 Carriage Contraptions
- 4 Create blocks and Items

## Mod spotlights[]

Mod spotlight by direwolf20 part 1 part 2 part 3 part 4

## Core Features[]

### **The Basics of Rotation**[]

A Rotating Encased belt block

Many machines and components in Create require Rotational Force to operate.

Any machine/component blocks that involves moving blocks or moving/crafting/converting item or entities (and the Cuckoo Clock), will require a certain amount of speed or higher in order to operate.

### **Generating and Transferring Rotational Force**[]

Components such as Shafts, Gearboxes, Gearshifts and Clutches only transfer, stop or convert rotation power, and do not have any speed requirement.

### **Changing Gears**[]

Just alone having components rotate is not enough. Sometimes more control over the speed of rotation is necessary. This is especially important for machines that require a *minimum level of speed* to operate (e.g. the Mechanical Mixer). To make this possible, some kinetic blocks have the ability to *speed up* or *slow down* connected components:

### Cogwheels[]

Cogwheels are not only useful for relaying rotation, but also serve as a simple way to control the speed. By attaching a large cogwheel diagonally to a regular sized one, one can double/half the speed of the other.

Powering the *large cogwheel* results in the *smaller* one turning at double the speed

Powering the *small cogwheel* results in the *larger* one turning at half the speed.

### Adjustable Chain Gearshift[]

The Adjustable Chain Gearshift, when used in combination with Encased Chain Drives, gives finer control over speed than cogwheels. It can increase *input* speed for attached chain drives, or decrease *output* speed of shafts connected to chain drives.

While acting as an input, the Adjustable Chain Gearshift will increase the speed of attached encased chain drives based on the analog redstone signal it receives. A full power of 15 will double all chain drives’ speed while values below will interpolate the factor from 2x to 1x.

While acting as an output, the Adjustable Chain Gearshift will decrease the speed of connected shaft. A full power of 15 will half the speed and values below will interpolate the factor from 0.5x to 1x.

When unpowered, the chain gearshift will not affect the speed at all and behaves like an encased chain drive.

### Rotation Speed Controller[]

While having a more expensive recipe, the Rotation Speed Controller also has the finest control over speed change. When a large cogwheel is attached to the controllers top, it will try its best to keep it spinning at the speed configured in the scroll field. When holding down *shift* while scrolling, the speed will increase/decrease by 1.

### Overpowering[]

Connecting faster components to other slower components directly will cause the faster network to overpower the rest, aligning the speed of the component network (that is, if the direction lines up).

### **Stress Units**[]

The machine/component blocks that do have a speed requirement will also have a stress impact

- **These blocks include:**
    - Mechanical Piston (sticky and non-sticky)
    - Mechanical Press
    - Millstone
    - Crushing Wheels
    - Mechanical Mixers
    - Mechanical Saw
    - Deployer
    - Mechanical Drill
    - Mechanical Crafter
    - Rope Pulley
    - Clockwork Bearing
    - Mechanical Bearing (unless used for power generation)
    - Encased Fan (unless used for power generation)
    - Cuckoo Clock
    - Mechanical Belts

### **Materials**[]

Create adds a few crafting ingredients for use throughout the mod. While some of them have few uses within Create itself at the moment, they are still handy connection points for pack-makers.

- Andesite Alloy, used for Andesite Casing and all the low-tier kinetic components.
- Brass, used in Brass Casing and more advanced kinetic blocks. Entry-point to the logistical components.
- Copper, generates in the world around surface level. Used for Copper Casing and fluid handling components, and used with Zinc to make Brass.
- Zinc, generates in the world. Used with Copper to make Brass.

### Other Materials[]

- Cinder Flour, made from crushing Netherrack.
- Polished Rose Quartz, made from using Sand Paper on craft-able Rose Quartz. Used in the crafting of Electron Tubes and mixing of Chromatic Compound.
- Powdered Obsidian, made from crushing Obsidian. Used in several filling recipes and in the compacting of Blaze Cake Bases.

### **Moving Contraptions**[]

Create allows you to move and animate block structures of any shape or form. This feature is extremely powerful as it proves useful in the field of automation, transportation and aesthetics.

In order to get the most out of this mechanic, it is helpful to know about the components and interactions involved in creating such structures.

1. Contraption Controllers
2. Contraption Assembly and Chassis Blocks elongated chonks
3. Portable Storage
4. Portable Actors

## Contraption Controllers[]

- Depending on the use case, different controllers can be used for mounting your structure. Some push, some pull, some rotate and some do it all at once.
- These blocks have specific spaces where the anchor of the structure needs to be, and some can be configured to react differently to being stopped.

### Mechanical Piston[]

Mechanical Pistons are kinetically powered counterparts to Minecraft’s Pistons. As such, they can push a line of blocks in front of them, and if sticky, pull the closest one back.

However, Create’s pistons do not work on their own. They require Piston Extension Poles added at the back, in order to be able to extend. When rotated, the piston will extend exactly as far as poles have been added to the back, rather than just 1 block space.

### Rope Pulley[]

The Rope Pulley moves attached blocks and structures vertically. Use Chassis, Slimeballs or Super Glue to move more than a single block.

When Powered by kinetics:

Starts moving the attached structure.

Speed and direction correlate to the incoming Rotation Speed.

### Mechanical Bearing[]

The Mechanical Bearing is used for rotating larger structures with rotational force.

When Powered by kinetics:

Starts rotating the attached blocks.

Use Chassis, Slime or Super Glue to move more than a single block. Blocks that attach to other blocks, such as levers, torches, or a Mechanical Saw will become part of the structure automatically.

Other attached Mechanical Bearings, if facing along the same axis as the original, will keep their alignment as the original rotates.

### Clockwork Bearing[]

The Clockwork Bearing is an advanced version of the Mechanical Bearing for rotating up to two clock hands according to the current in-game time.

When Powered by kinetics:

Starts rotating the attached structure towards the current hour. If an independent second structure exists in front of the first one, it will serve as the minute hand.

### Cart Assembler[]

When placed on a Rail, the Cart Assembler can assemble and disassemble moving structures onto passing minecarts. Similarly to rotating structures, having a Mechanical Bearing in the structure will cause the attached part to keep the same alignment as the cart moves.

### Single Cart Contraptions[]

Single Cart contraptions as well as Carriage contraptions can carry items, liquids, or mobs, provided they have the correct storage blocks. They can also use the Mechanical Saw, Drill, Harvester, Plough or the Portable Storage Interface to interact with the world.

### Carriage Contraptions[]

Carriage Contraptions are about the same, except their movement is smoother and thus it is easier to walk or ride on them without falling off.

## Create blocks and Items[]

Source: https://github.com/Creators-of-Create/Create/wiki 1st May 2020