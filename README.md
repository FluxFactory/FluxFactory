# FluxFactory

A hardcore tech-focused Minecraft modpack inspired by the progression of *GregTech: New Horizons*, but built around **Redstone Flux (RF)**. As an employee of **MineCorp**, your goal is to build massive, automated factories to fulfill corporate contracts, unlock new technologies, and ultimately lead the charge into space.

**Minecraft Version:** 1.21.1

## Repository Structure

This repository is for the documentation and planning of the FluxFactory modpack. The actual modpack files and implementation are not stored here.

-   **/docs**: Contains the core design documents, progression plans, and rationale behind the modpack's features.
-   **/drafts**: A place for work-in-progress ideas, KubeJS script examples, and questline text before they are finalized.
-   **/assets**: Contains images, diagrams, or flowcharts used in the documentation.
-   `README.md`: This file! A high-level overview and project status tracker.

## Core Concept

*   **GTNH-Inspired Progression:** Deep, multi-stage progression without the `GregTech` mod itself.
*   **Corporate Orders:** Advance through technology tiers by completing resource shipment quests for your corporate overlords.
*   **Blueprint Research:** Unlock new machines and recipes by researching them first, rather than having everything available from the start.
*   **RF-Based Energy:** All technology is powered by RF, with added complexity like power loss and tiered energy systems.

### Progression Tiers & To-Do

- [ ] **Tier 0 - Stone Age**: Vanilla-like start. Establish basic survival and resource gathering.
- [ ] **Tier 1 - LV (Low Voltage)**: Build your first simple RF generators and machines (`Thermal Series`, early `Mekanism`). Fulfill first corporate order.
- [ ] **Tier 2 - MV (Medium Voltage)**: Unlock more complex production chains and the first multi-block structures (`Immersive Engineering`).
- [ ] **Tier 3 - HV (High Voltage)**: Access digital storage and mass automation (`Applied Energistics 2`). Prepare for the space race.
- [ ] **Tier 4 - EV+ (Space Age)**: Build a rocket, travel to the Moon and other planets to find unique, end-game resources.

### Key Mods to Include

*   **Primary Tech & Automation:**
    - [ ] Thermal Series
    - [ ] Mekanism
    - [ ] Immersive Engineering
    - [ ] Create
    - [ ] Applied Energistics 2 / Refined Storage
*   **Power Generation:**
    - [ ] Powah!
    - [ ] Bigger Reactors
*   **Space & Exploration:**
    - [ ] Ad Astra / Advanced Rocketry (TBD)
    - [ ] Biomes O' Plenty
    - [ ] YUNG's Better Structures (Mineshafts, Strongholds, etc.)
*   **Core Mechanics & Quests:**
    - [ ] FTB Quests
    - [ ] Game Stages / KubeJS (For recipe gating/research)
*   **Quality of Life (QoL):**
    - [ ] JourneyMap
    - [ ] Just Enough Items (JEI)
    - [ ] Mouse Tweaks

### Customization & Balancing

- [ ] **Corporate Orders Questline**: Design the main quest tree in `FTB Quests` to guide players through the tiers.
- [ ] **Blueprint Research System**: Implement a system where players must craft/submit items to unlock recipe stages (`Game Stages`).
- [ ] **Tiered Recipe Gating**: Use scripts (`KubeJS`/`CraftTweaker`) to lock higher-tier machines and components behind progression.
- [ ] **Custom Energy Mechanics**: Configure/script power loss over distance for certain cables to encourage thoughtful base design.
- [ ] **Recipe Integration**: Create custom recipes to make mods flow into each other seamlessly.
- [ ] **Config Tweaks**: Adjust ore generation, machine power usage, and other values for balance.