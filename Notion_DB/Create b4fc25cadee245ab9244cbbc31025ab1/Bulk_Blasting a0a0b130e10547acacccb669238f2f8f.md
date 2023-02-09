# Bulk_Blasting

## Encased Fan

### Renewable

Yes

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

## Rotational Power stats

### Kinetic Stress impact

2x RPM

### Kinetic Stress capacity

16x RPM

### Rotational Speed generated

4 RPM

The **Encased Fan** is a mechanical component that can create air streams. Encased Fans are used for moving entities, vertical transport of items, Bulk Washing, Bulk Blasting, Bulk Haunting, and Bulk Smoking.

The Encased Fan connects to other rotational components from the back.

## Contents

- 1 Obtaining
    - 1.1 Crafting
- 2 Usage
    - 2.1 Pushing and Pulling Entities
    - 2.2 Vertical Item Transport
    - 2.3 Power Generation
    - 2.4 Bulk Item Processing
    - 2.5 Mob Interaction
        - 2.5.1 Bulk Item Processing Speed
        - 2.5.2 Bulk Item Processing Recipes
- 3 History

## Obtaining[]

### Crafting[]

## Usage[]

### Pushing and Pulling Entities[]

When powered by Rotational Force, an Encased Fan creates an air stream that extends several blocks in front of it. This air stream pushes entities away from the fan or pulls entities towards it depending on the direction of the rotation that the fan receives. Powering an Encased Fan with faster rotational force will cause its air stream to be stronger and faster.

Items will always be pushed, but mobs or players won’t be pushed until the Fan is running at least 4 rpm. The maximum push and pull distance can be changed in the Config.

### Vertical Item Transport[]

A fan creating a vertical airstream going upwards can be connected to chutes. Items inserted into the chutes will be pushed/pulled upwards. The range of the item transport depends on the rotation speed of the fan.

### Power Generation[]

Before version 0.5 was released, an Encased Fan could generate Rotational Force at a speed of 16 RPM when placed above a Magma Block, Lava, Fire, or Campfire and powered via Redstone. After version 0.5, this feature was removed.

### Bulk Item Processing[]

When the air stream of an Encased Fan passes through certain blocks, the air stream downstream will apply the respective processing to items.

- Washing:
    - Water
- Smoking:
    - Fire
    - Campfire
    - Empty Blaze Burner lit with Flint and Steel
    - Blaze Burner (smouldering)
- Blasting:
    - Lava
    - Blaze Burner (Fueled)
- Haunting:
    - Soul Fire
    - Soul Campfire
    - Empty Blaze Burner lit with Flint and Steel and right clicked with Soul Sand or Soul Soil.

The respective recipes are applied to item entities when they sit in the air stream, whether they are in the world, on a Mechanical Belt, or on a Depot. These recipes can be applied to multiple items at once.

A few other solid blocks are transparent to the fan’s air stream. These blocks may be useful for building bulk item processing setups, as they can hold back lava or water while allowing the air stream through.

- Fences
- Iron Bars
- Sail Frames

### Mob Interaction[]

When the player or a mob steps into a Bulk Processing stream, various effects may be applied.

- Smoking sets the entity on fire and deals 2 or 3 damage depending on Difficulty.
- Blasting sets the entity on fire and deals 3, 4, or 6 damage depending on Difficulty.
- Washing streams extinguish entities on fire and deal 2 damage to Endermen, Blazes, and Snow Golems.
- Haunting streams apply Slowness II and Blindness.

### Bulk Item Processing Speed[]

All forms of Bulk Processing (Smoking, Blasting, Haunting, and Washing) process items at the same speeds. Multiple fans applying the same processing effect on the same block divide the processing time. For example, two fans creating an air stream through water will process the same amount of items twice as fast as one fan. However, different stack sizes take a different amount of time to process, as listed below:

Note that if a recipe’s output is also a valid input for a different recipe (such as Cobblestone → Stone → Smooth Stone), the second recipe will start being processed immediately after the previous one is finished. Use Depots with filtered Brass Funnels, Mechanical Arms with filtered outputs, or Mechanical Belts set to the correct speed (as listed above).

### Bulk Item Processing Recipes[]

- Bulk Smoking will apply any recipe that can be applied in Smokers.
- Bulk Blasting will apply any recipe that can be applied in Furnaces but not Smokers.
    - **Warning:** Passing incompatible items through Bulk Blasting will incinerate them.
- Bulk Washing will apply any recipe listed below:
- Bulk Haunting will apply any recipe listed below:

## History[]

- 0.5: Can no longer be used as a power generator.
- 0.4c: Added Bulk Haunting Recipes.
- 0.2.4: Washing Fans damage Endermen.
- 0.2.3: Can now be moved in Contraptions.
- 0.2: No longer affect their environment in both directions.
- 0.1: Introduced.