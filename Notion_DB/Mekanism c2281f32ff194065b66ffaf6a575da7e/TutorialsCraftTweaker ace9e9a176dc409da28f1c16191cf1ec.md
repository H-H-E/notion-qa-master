# TutorialsCraftTweaker

Mekanism has native support for CraftTweaker since version 1.12.1-9.4.1.

## Requirements

- Mekanism 9.4.1 or higher
- MTLib

## How does it work?

For almost every machine Mekanism adds there is a way to add recipes to it through CraftTweaker. One that doesn’t have any custom recipes is the EnergizedSmelter, that uses the default Minecraft furnace recipes, which could also be added through CraftTweaker.

As an example says more than thousand words, you can find an example at the bottom of this page. Every part has the following layout:

Name of the machine

Which entry is what

An example to add a recipe

Which entry is what

An example to remove a recipe

Note that // is being used as comments in ZenScript files and things between [ ] are optional.

## Example file

//Chemical Crystallizer

//InputGas, OutputStack

mods.mekanism.chemical.crystallizer.addRecipe(, );

//OutputStack[, InputGas]

mods.mekanism.chemical.crystallizer.removeRecipe(, );

//Chemical Dissolution Chamber

//InputStack, OutputGas

mods.mekanism.chemical.dissolution.addRecipe(, );

//OutputGas[, InputStack]

mods.mekanism.chemical.dissolution.removeRecipe(, );

//Chemical Infuser

//InputGas1, InputGas2, OutputGas

mods.mekanism.chemical.infuser.addRecipe(, , );

//OutputGas[, InputGas1, InputGas2]

mods.mekanism.chemical.infuser.removeRecipe(, , );

//Chemical Injection Chamber

//InputStack, InputGas, OutputStack

//InputGas only accepts “”, “” or “”

mods.mekanism.chemical.injection.addRecipe(<minecraft:hardened_clay:1>, , );

//OutputStack[, InputStack, InputGas]

mods.mekanism.chemical.injection.removeRecipe(, , );

//Chemical Oxidizer

//InputStack, OutputGas

mods.mekanism.chemical.oxidizer.addRecipe(, );

//OutputGas[, InputStack]

mods.mekanism.chemical.oxidizer.removeRecipe(, );

//Chemical Washer

//InputGas, OutputGas

mods.mekanism.chemical.washer.addRecipe(, );

//OutputGas[, InputGas]

mods.mekanism.chemical.washer.removeRecipe(, );

//Combiner

//InputStack, InputStack, OutputStack

mods.mekanism.combiner.addRecipe( * 4, , );

//OutputStack[, InputStack, InputStack]

mods.mekanism.combiner.removeRecipe(, , );

//Osmium Compressor

//InputStack, InputGas, OutputStack

mods.mekanism.compressor.addRecipe(, , );

//OutputStack[, InputStack, InputGas]

mods.mekanism.compressor.removeRecipe(, , );

//Crusher

//InputStack, OutputStack

mods.mekanism.crusher.addRecipe(<minecraft:double_plant:4>,  * 5);

//OutputStack, InputStack

mods.mekanism.crusher.removeRecipe(, );

//Energized Smelter

//InputStack, OutputStack

mods.mekanism.smelter.addRecipe(, );

//InputStack[, OutputStack]

mods.mekanism.smelter.removeRecipe(, );

//Enrichment Chamber

//InputStack, OutputStack

mods.mekanism.enrichment.addRecipe(<minecraft:coal_block>,  * 9);

//InputStack[, OutputStack]

mods.mekanism.enrichment.removeRecipe(<minecraft:mossy_cobblestone>, );

//Metallurgic Infuser

//InfusionString, InputInfusion, InputStack, OutputStack //InfusionString = CARBON;TIN;DIAMOND;REDSTONE;FUNGI;BIO;OBSIDIAN

mods.mekanism.infuser.addRecipe(“OBSIDIAN”, 20, <minecraft:coal_block>, );

//OutputStack[, InputStack, InfusionString]

mods.mekanism.infuser.removeRecipe();

//Purification Chamber

//InputStack, InputGas, OutputStack

mods.mekanism.purification.addRecipe(, , );

//OutputStack[, InputStack, InputGas]

mods.mekanism.purification.removeRecipe(, , );

//Pressurised Reaction Chamber

//InputStack, InputFluid, InputGas, OutputStack, OutputGas, InputRF, Time in Ticks

mods.mekanism.reaction.addRecipe(, , ,  * 8, , 50000, 2000);

//OutputStack[, OutputGas, InputStack, InputFluid, InputGas]

mods.mekanism.reaction.removeRecipe(, , , , );

//Precision Sawmill

//InputStack, OutputStack1, OutputStack2, Chance

mods.mekanism.sawmill.addRecipe(,  * 3,  * 3, 0.5);

//InputStack[, OutputStack1, OutputStack2]

mods.mekanism.sawmill.removeRecipe(, , );

//Electrolytic Separator

//InputFluid, InputRF, OutputGas1, OutputGas2

mods.mekanism.separator.addRecipe(, 5000, , );

//InputFluid[, OutputGas1, OutputGas2]

mods.mekanism.separator.removeRecipe(, , );

//Solar Evaporation

//InputFluid, OutputFluid

mods.mekanism.thermalevaporation.addRecipe(, );

//InputFluid[, OutputFluid]

mods.mekanism.thermalevaporation.removeRecipe(, );

//Solar Neutron Activator

//InputGas, OutputGas

mods.mekanism.solarneutronactivator.addRecipe(, );

//InputGas[, OutputGas]

mods.mekanism.solarneutronactivator.removeRecipe(, );