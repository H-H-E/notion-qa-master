# Sequenced_Gearshift

## Sequenced Gearshift

### Renewable

No

### Stackable

Yes (64)

### Tools

### Blast resistance

6

### Hardness

1.5

### Solid block

Yes

### Full block

Yes

### Transparent

Yes

### Luminant

No

### Flammable

No

### Catches fire from lava

No

The **Sequenced Gearshift** allows finer control over Rotational power, allowing multiple changes to the rotation over a period of time.

## Contents

- 1 Obtaining
    - 1.1 Crafting
- 2 Usage
- 3 History

## Obtaining[]

### Crafting[]

## Usage[]

The Sequenced Gearshift can be given up to 5 commands at a time. Each command can be adjusted by hovering over them and scrolling in the interface.

The first column consists of the commands **Turn by angle, Turn by Piston, Timed Delay, Await New Redstone Pulse, and End.** The first two are simply different measurements of rotation corresponding to Mechanical Pistons and Mechanical Bearings, the third makes the Gearshift wait before proceeding to the next command, while the fourth stops the sequence until the Gearshift receives another pulse. End signifies the end of a sequence, but is not necessary for a sequence to be completed.

The second column adjusts the measurements for each command. Up to 360 Degrees for Turn, 128 blocks for Piston, and 30 seconds for Wait.

The third column adjusts speed and direction. Here, rotation can be doubled, reversed, both, or neither.

A Redstone Comparator can be used to detect what instruction a Sequenced Gearshift is on. It will output a signal strength of up to 5, regardless of how many instructions are in the Gearshift.

## History[]

- 0.5: Recipe changed.
- 0.3.1: Can now be told to wait for an additional pulse
- 0.3:
    - Now emit a Redstone Comparator signal based on their current instruction index
    - The Piston instruction for sequencers can now accept distances up to 128m
- 0.2: Introduced.