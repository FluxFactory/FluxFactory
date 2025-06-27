Below is a consolidated list of custom machines, their functions, analogies, and recipe examples.

*   **`Pulverizer/Macerator/Crusher`**
    *   **Function:** A basic grinder that turns raw ore into `crushed_ore`. It is the first step in ore doubling.
    *   **Analogy:** A less efficient Thermal Series Pulverizer or Mekanism Crusher.
    *   **Recipe Example:** `1 Iron Ore -> 1 Crushed Iron`
    *   **Notes:** This machine is for initial crushing. Further processing is required for optimal yield.

*   **`Washer/Washing Machine`**
    *   **Function:** Takes `crushed_ore` and water to produce `purified_ore_dust` and a byproduct (e.g., Stone Dust). This step slightly increases overall ore yield and is a prerequisite for advanced separation.
    *   **Analogy:** A simplified version of an Immersive Engineering Sluice Box.
    *   **Recipe Example:** `1 Crushed Iron + Water -> 1 Purified Iron Dust + 1 Small Pile of Stone Dust`

*   **`Component Press`**
    *   **Function:** A simple machine that uses press plates (new items) to form ingots into basic components.
    *   **Analogy:** A dedicated, slower version of the Thermal Multiservo Press or a Metal Press.
    *   **Recipe Example:** `1 Iron Ingot + Wire Press Plate -> 2 Iron Wire` or `1 Iron Ingot + Plate Press Plate -> 1 Iron Plate`
    *   **Notes:** Requires specific "Press Plates" which are crafted in the `Tool Forge`.

*   **`Arc Furnace` (Multiblock)**
    *   **Function:** A high-temperature furnace for smelting `purified_ore_dust` and other refined dusts into ingots. More efficient than basic furnaces for processed materials.
    *   **Analogy:** A custom, tiered version of a standard furnace, or an early-game GregTech Electric Furnace.
    *   **Recipe Example:** `1 Purified Iron Dust -> 1 Iron Ingot` or `1 Iron Dust + 1 Coal Dust -> 1 Iron Ingot`

*   **`Industrial Blast Furnace` (Multiblock)**
    *   **Function:** The primary machine for producing steel and other high-temperature alloys. Requires a heat source (e.g., from a separate block) and a reducing agent (e.g., Coal Coke).
    *   **Analogy:** A blend of the Immersive Engineering Blast Furnace and the GregTech Blast Furnace.
    *   **Recipe Example:** `2 Iron Ingots + 4 Coal Coke -> 1 Steel Ingot`
    *   **Notes:** Requires a dedicated `High-Temperature Heater` multiblock for operation.

*   **`Centrifugal Separator` (Multiblock)**
    *   **Function:** Takes `purified_ore_dust` and separates it into a primary metal dust and a secondary, smaller pile of byproduct dust. This is the key to obtaining secondary metals like Nickel, Silver, or Lead from primary ores.
    *   **Analogy:** A core GregTech mechanic, but RF-powered.
    *   **Recipe Example:** `2 Purified Iron Dust -> 2 Iron Dust + 1 Small Pile of Nickel Dust`
    *   **Notes:** The resulting primary and secondary dusts are then processed in the `Arc Furnace`.

*   **`Chemical Reactor` (Multiblock)**
    *   **Function:** A multi-input machine that processes fluids and items to create intermediate chemical products, such as acids for ore leaching or polymers for circuits.
    *   **Analogy:** A unified version of Mekanism/GregTech chemical machines, acting as a chemical plant, mixer, and polymerizer.
    *   **Recipe Example:** `Sulfur Dust + Oxygen -> Sulfur Dioxide Gas` (Reaction), `100mB Naphtha + 50mB Oxygen Gas -> 1 Plastic Sheet` (Polymerization).

*   **`Circuit Assembler`**
    *   **Function:** A dedicated, multi-step machine for crafting electronic circuits. It would require inputs like etched silicon wafers, fine wire, and plastic substrates, assembled over time. This replaces simple crafting grid recipes for circuits.
    *   **Analogy:** A simplified version of the GregTech Circuit Assembler.
    *   **Recipe Example:** `1 Etched Wafer + 4 Fine Copper Wire + 1 Plastic Sheet -> 1 Basic Control Circuit`
    *   **Notes:** Requires inputs from the `Silicon Melter`, `Precision Machining Center`, `Etching Chamber`, `Chemical Reactor` (for plastics), and `Component Press`.

*   **`Precision Laser Engraver` (Multiblock)**
    *   **Function:** The top-tier machine for creating advanced processing units. It uses powerful lasers, lenses (new items), and specific gas atmospheres to etch complex patterns onto silicon wafers.
    *   **Analogy:** The end-game circuit manufacturing found in advanced tech packs.
    *   **Recipe Example:** `1 Polished Silicon Wafer + 1 Gallium Arsenide Lens + Nitrogen Gas -> 1 Advanced Processor Wafer`
    *   **Notes:** Requires inputs from the `Silicon Melter`, `Precision Machining Center`, and `Cryogenic Separator`.
 
*   **`Quantum Entangler`**
    *   **Function:** A very late-game, power-hungry machine used to create the entangled singularities for AE2's Quantum Network Bridge or similar high-tier components.
    *   **Analogy:** A thematic, end-game "magic block" that serves a specific, high-cost purpose.
    *   **Notes:** This machine is specifically designed to integrate with Applied Energistics 2's end-game mechanics.

*   **`Tool Forge`**
    *   **Function:** Crafts specialized tools and machine components, including the "Press Plates" required by the `Component Press`.
    *   **Analogy:** A more advanced crafting station or a simplified Immersive Engineering Metal Press for tool parts.
    *   **Recipe Example:** `2 Steel Ingot + 1 Diamond -> 1 Wire Press Plate`

*   **`High-Temperature Heater` (Multiblock)**
    *   **Function:** Generates and transfers extreme heat to adjacent multiblocks, specifically designed to power the `Industrial Blast Furnace`.
    *   **Analogy:** A dedicated heat source, similar to a high-tier boiler or combustion chamber.
    *   **Recipe Example:** Consumes high-calorific fuels (e.g., Coal Coke, Liquid Fuel) to produce heat.

*   **`Electrolyzer` (Multiblock)**
    *   **Function:** Splits fluids (primarily water) into their constituent gases using electrical energy.
    *   **Analogy:** Mekanism Electrolytic Separator.
    *   **Recipe Example:** `1000mB Water -> 500mB Oxygen Gas + 1000mB Hydrogen Gas`

*   **`Cryogenic Separator` (Multiblock)**
    *   **Function:** Cools and compresses atmospheric air to separate it into its various gaseous components (Nitrogen, Oxygen, Argon, etc.).
    *   **Analogy:** An advanced version of a gas separator, similar to some GregTech processes.
    *   **Recipe Example:** `1000mB Air -> 780mB Nitrogen Gas + 210mB Oxygen Gas + 10mB Argon Gas`

*   **`Silicon Melter`**  molten silicon, which can then be cast into ingots or crystal boules.
    *   **Analogy:** A specialized furnace for high-purity material melting.
    *   **Recipe Example:** `4 Silicon Ore -> 1000mB Molten Silicon`

*   **`Etching Chamber`**
    *   **Function:** Uses corrosive chemicals (e.g., Sulfuric Acid) to etch patterns onto raw silicon wafers, preparing them for circuit assembly.
    *   **Analogy:** A chemical bath for micro-fabrication.
    *   **Recipe Example:** `1 Raw Silicon Wafer + 100mB Sulfuric Acid -> 1 Etched Wafer`

*   **`Precision Machining Center`**
    *   **Function:** A versatile, high-precision machine for shaping advanced materials. It can perform cutting, grinding, and polishing operations depending on the recipe and installed tool head (e.g., saw blade, grinding wheel, polishing pad).
    *   **Analogy:** A combination of a CNC machine, a lathe, and a surface grinder.
    *   **Recipe Example:** `1 Silicon Boule + Saw Blade -> 8 Raw Silicon Wafers`, `1 Gallium Arsenide Crystal + Grinding Wheel -> 1 Gallium Arsenide Lens`, `1 Etched Wafer + Polishing Pad -> 1 Polished Silicon Wafer`.

*   **`Coke Oven` (Multiblock)**
    *   **Function:** Processes coal into coke and creosote oil. Essential for early steel production and various chemical processes.
    *   **Analogy:** Immersive Engineering Coke Oven, GregTech Coke Oven.
    *   **Recipe Example:** `8 Coal -> 8 Coal Coke + 1000mB Creosote Oil`

*   **`Vacuum Freezer`**
    *   **Function:** Rapidly cools hot ingots (e.g., from the Industrial Blast Furnace) into usable ingots. This is crucial for processing high-temperature alloys.
    *   **Analogy:** GregTech Vacuum Freezer.
    *   **Recipe Example:** `1 Hot Steel Ingot -> 1 Steel Ingot`

*   **`Distillation Tower` (Multiblock)**
    *   **Function:** Separates complex fluid mixtures (like crude oil, chemical solutions, or even some gases) into their constituent components through fractional distillation.
    *   **Analogy:** GregTech Distillation Tower, Mekanism Fractionating Column.
    *   **Recipe Example:** `1000mB Crude Oil -> 400mB Light Oil + 300mB Medium Oil + 200mB Heavy Oil + 100mB Bitumen`

*   **`Crystallizer` (Multiblock)**
    *   **Function:** Processes specific fluid solutions or highly purified dusts to grow crystals or form solid materials through controlled crystallization.
    *   **Analogy:** GregTech Crystallization Chamber.
    *   **Recipe Example:** `1000mB Silicon Solution -> 1 Silicon Crystal`

*   **`Extruder` (Multiblock)**
    *   **Function:** Shapes molten metals or heated plastic into specific forms like rods, pipes, or wires by forcing the material through a die.
    *   **Analogy:** GregTech Extrusion Machine.
    *   **Recipe Example:** `144mB Molten Copper + Rod Die -> 1 Copper Rod`

*   **`Combustion Generator` (Multiblock)**
    *   **Function:** Generates large amounts of RF by efficiently burning high-calorific liquid or gaseous fuels. This is a dedicated power generation unit, distinct from the High-Temperature Heater.
    *   **Analogy:** Immersive Engineering Biodiesel Generator, Mekanism Gas-Burning Generator.
    *   **Recipe Example:** `100mB Biofuel -> 10000 RF` (over time)

*   **`Industrial Excavator` (Multiblock)**
    *   **Function:** A very late-game, massive machine that extracts large quantities of specific ores from hidden, chunk-specific veins. Requires significant power and maintenance, and encourages exploration.
    *   **Analogy:** Immersive Engineering Excavator.
    *   **Recipe Example:** Operates continuously in a chunk with an ore vein, producing `Iron Ore`, `Copper Ore`, etc.

*   **`Pyrolyzer` (Multiblock)**
    *   **Function:** Processes organic materials (like wood, biomass, or certain crops) at high temperatures in an oxygen-starved environment to produce charcoal, creosote oil, and various gases or heavy oils.
    *   **Analogy:** GregTech Pyrolyze Oven, or a more advanced Immersive Engineering Coke Oven for biomass.
    *   **Recipe Example:** `8 Wood Logs -> 8 Charcoal + 500mB Creosote Oil + 200mB Wood Gas`

*   **`Cracker Unit` (Multiblock)**
    *   **Function:** Breaks down complex hydrocarbon fluids (like heavy oil or diesel) into lighter, more refined fuels or chemical feedstocks through a catalytic cracking process.
    *   **Analogy:** GregTech Cracker Unit, Mekanism Cracking Unit.
    *   **Recipe Example:** `1000mB Heavy Oil -> 600mB Light Oil + 300mB Naphtha + 100mB Sulfur Gas`

*   **`Electromagnetic Separator` (Multiblock)**
    *   **Function:** Separates mixed dusts or fine particles based on their magnetic properties. Useful for isolating magnetic metals (like iron or nickel) from non-magnetic ones.
    *   **Analogy:** GregTech Electromagnetic Separator.
    *   **Recipe Example:** `2 Iron Dust + 1 Nickel Dust -> 2 Iron Dust (Magnetic) + 1 Nickel Dust (Non-Magnetic)`

*   **`Implosion Compressor` (Multiblock)**
    *   **Function:** Uses controlled explosions or immense pressure to transform materials, often converting dusts into gems or compacting materials into denser forms.
    *   **Analogy:** GregTech Implosion Compressor.
    *   **Recipe Example:** `1 Diamond Dust + 1 TNT -> 1 Diamond` (with a chance of byproduct)

*   **`Boiler` (Multiblock)**
    *   **Function:** Generates large quantities of high-pressure steam from water using a heat source (e.g., from the `High-Temperature Heater` or dedicated fuel). Essential for steam-driven turbines or chemical processes.
    *   **Analogy:** GregTech Large Boilers, Railcraft Boiler.
    *   **Recipe Example:** `1000mB Water + Heat -> 1000mB Steam`

*   **`Turbine Generator` (Multiblock)**
    *   **Function:** Converts the kinetic energy of high-pressure steam, hot gases, or plasma into electrical RF energy by spinning a rotor.
    *   **Analogy:** GregTech Large Turbines, Immersive Engineering Steam Turbine.
    *   **Recipe Example:** `1000mB Steam -> X RF` (over time, efficiency based on turbine design)

*   **`Fluid Solidifier` (Multiblock)**
    *   **Function:** Takes fluid inputs and solidifies them into blocks or items, often requiring cooling or a catalyst. Useful for creating building materials or specific components from fluid processes.
    *   **Analogy:** GregTech Fluid Solidifier.
    *   **Recipe Example:** `1000mB Molten Plastic -> 1 Plastic Block` or `100mB Liquid Silicon -> 1 Silicon Wafer (Raw)`

*   **`Packaging Machine` (Multiblock)**
    *   **Function:** Automatically combines items into larger stacks, blocks, or specific packages (e.g., crafting 9 ingots into a block, or creating packed items for transport).
    *   **Analogy:** GregTech Packaging Machine, Mekanism Compressing Factory.
    *   **Recipe Example:** `9 Iron Ingot -> 1 Iron Block` or `4 Rubber -> 1 Rubber Block`

*   **`High Energy Charger`**
    *   **Function:** A specialized machine for rapidly charging high-tier energy storage items (e.g., advanced batteries, energy orbs) that require significant power input.
    *   **Analogy:** GregTech High Energy Charger.
    *   **Recipe Example:** Charges `Lapotronic Energy Orb` at a very high RF/t rate.

*   **`Chemical Dissolution Chamber`**
    *   **Function:** Dissolves raw ores or processed materials into a liquid slurry using specific chemical reagents (e.g., Sulfuric Acid). This is the first step in Mekanism's advanced ore processing chain.
    *   **Analogy:** Mekanism Chemical Dissolution Chamber.
    *   **Recipe Example:** `1 Iron Ore + 100mB Sulfuric Acid -> 1000mB Dirty Iron Slurry`
    *   **Notes:** Requires a continuous supply of the dissolving agent.

*   **`Chemical Injection Chamber`**
    *   **Function:** Processes ores or materials by injecting them with a specific gas, often to produce shards or other intermediate forms. Part of Mekanism's 4x/5x ore processing.
    *   **Analogy:** Mekanism Chemical Injection Chamber.
    *   **Recipe Example:** `1 Iron Ore + 100mB Hydrogen Chloride -> 4 Iron Shards`

*   **`Purification Chamber`**
    *   **Function:** Processes ores into clumps using oxygen gas, typically as part of a 3x ore processing chain.
    *   **Analogy:** Mekanism Purification Chamber.
    *   **Recipe Example:** `1 Iron Ore + 100mB Oxygen Gas -> 3 Iron Clumps`

*   **`Chemical Washer`**
    *   **Function:** Cleans dirty ore slurries (from the Chemical Dissolution Chamber) into clean slurries using water.
    *   **Analogy:** Mekanism Chemical Washer.
    *   **Recipe Example:** `1000mB Dirty Iron Slurry + 1000mB Water -> 1000mB Clean Iron Slurry`

*   **`Chemical Crystallizer`**
    *   **Function:** Converts clean ore slurries into crystals, which can then be further processed into dusts.
    *   **Analogy:** Mekanism Chemical Crystallizer.
    *   **Recipe Example:** `1000mB Clean Iron Slurry -> 1 Iron Crystal`

*   **`Chemical Oxidizer`**
    *   **Function:** Converts certain solid materials (like sulfur or yellow cake uranium) into their gaseous forms.
    *   **Analogy:** Mekanism Chemical Oxidizer.
    *   **Recipe Example:** `1 Sulfur Dust -> 100mB Sulfur Dioxide Gas`

*   **`Chemical Infuser`**
    *   **Function:** Combines two different gases to produce a new gas. Essential for creating complex chemical reagents.
    *   **Analogy:** Mekanism Chemical Infuser.
    *   **Recipe Example:** `100mB Sulfur Dioxide Gas + 100mB Oxygen Gas -> 100mB Sulfur Trioxide Gas`

*   **`Rotary Condensentrator`**
    *   **Function:** Converts gases into liquids and vice-versa. Crucial for managing fluid and gas states in complex chemical processes.
    *   **Analogy:** Mekanism Rotary Condensentrator.
    *   **Recipe Example:** `1000mB Water Vapor -> 1000mB Water` (liquid) or `1000mB Water -> 1000mB Water Vapor` (gas)

*   **`Thermal Evaporation Plant` (Multiblock)**
    *   **Function:** Produces brine from water, which is a key component for various chemical reactions, including the production of sodium and chlorine.
    *   **Analogy:** Mekanism Thermal Evaporation Plant.
    *   **Recipe Example:** `1000mB Water -> 100mB Brine`
