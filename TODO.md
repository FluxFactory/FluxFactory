# FluxFactory Modpack Development To-Do List

This document outlines the actionable steps required to develop the FluxFactory modpack, based on the core concepts and progression defined in the project documentation.

## I. Project Setup & Initial Environment

- [ ] **Set up Development Environment:**
    - [ ] Install Minecraft 1.21.1 client.
    - [ ] Install a launcher (e.g., MultiMC/Prism Launcher) for easy instance management.
    - [ ] Set up a dedicated modpack instance for FluxFactory (1.21.1 Forge/NeoForge).
    - [ ] Configure IDE (e.g., VS Code) for KubeJS/CraftTweaker script development.
- [ ] **Establish Version Control:**
    - [ ] Initialize Git repository for modpack configuration files (excluding actual mod JARs).
    - [ ] Set up `.gitignore` to exclude unnecessary files (logs, temporary files, mod JARs if not managed by a manifest).

## II. Core Mod Integration (Initial Pass)

- [ ] **Add Essential QoL Mods:**
    - [ ] Just Enough Items (JEI)
    - [ ] JourneyMap
    - [ ] Mouse Tweaks
    - [ ] The One Probe / HWYLA / WTHIT
- [ ] **Add Primary Tech & Automation Mods:**
    - [ ] Thermal Series (Foundation, Expansion, Dynamics, etc.)
    - [ ] Mekanism (Generators, Tools, etc.)
    - [ ] Immersive Engineering
    - [ ] Create
    - [ ] Applied Energistics 2 / Refined Storage (Choose one, or integrate both carefully)
- [ ] **Add Power Generation Mods:**
    - [ ] Powah!
    - [ ] Bigger Reactors
- [ ] **Add World Generation & Exploration Mods:**
    - [ ] Biomes O' Plenty
    - [ ] YUNG's Better Structures (Mineshafts, Strongholds, Dungeons, etc.)
- [ ] **Add Core Mechanics & Questing Mods:**
    - [ ] FTB Quests
    - [ ] Game Stages (for recipe/stage gating)
    - [ ] KubeJS / CraftTweaker (for scripting custom recipes, events, etc.)
- [ ] **Initial Mod Compatibility Check:**
    - [ ] Launch the game with all selected mods.
    - [ ] Address any immediate crashes or major conflicts.

## III. Progression System (Gating & Research)

- [ ] **Blueprint Research System Implementation:**
    - [ ] Define specific `Game Stages` for each technology tier (e.g., `fluxfactory:lv_unlocked`, `fluxfactory:mv_unlocked`).
    - [ ] Design the "Blueprint" item(s) or mechanism that players must craft/submit.
    - [ ] Use KubeJS to create recipes for blueprints that grant `Game Stages` upon completion/submission.
    - [ ] Implement initial blueprint recipes for Tier 1 (LV).
- [ ] **Tiered Recipe Gating:**
    - [ ] Identify key machines/items for each tier (e.g., LV machines, MV multi-blocks, HV AE2 components).
    - [ ] Use KubeJS to gate these recipes, requiring specific `Game Stages` to be active.
    - [ ] Ensure progression is linear and requires unlocking previous tiers.

## IV. Questing System (Corporate Orders)

- [ ] **Design Main Quest Tree:**
    - [ ] Outline the full "Corporate Orders" questline in FTB Quests.
    - [ ] Plan quest objectives, rewards, and dependencies for each tier.
- [ ] **Implement Tier 0 Quests (Stone Age):**
    - [ ] Basic survival, crafting tools, finding resources.
- [ ] **Implement Tier 1 Quests (LV):**
    - [ ] First power generation, basic automation.
    - [ ] "Corporate Order: Basic Metals" (e.g., ship 128 processed iron/copper).
- [ ] **Implement Tier 2 Quests (MV):**
    - [ ] Multi-block construction, more complex processing.
    - [ ] "Corporate Order: Advanced Components" (e.g., ship steel casings, treated wood).
- [ ] **Implement Tier 3 Quests (HV):**
    - [ ] Digital storage, advanced automation, rocket components.
    - [ ] "Corporate Order: Pre-Flight Assembly" (e.g., ship rocket parts, advanced circuits).
- [ ] **Implement Tier 4 Quests (EV+ / Space Age):**
    - [ ] Space travel, lunar base, unique resource acquisition.
    - [ ] "Corporate Order: Extraterrestrial Resources" (e.g., ship lunar regolith, alien alloys).
- [ ] **Add Quest Rewards & Penalties:**
    - [ ] Ensure rewards are balanced and encourage progression.
    - [ ] Consider optional penalties for failing certain objectives (if applicable).

## V. Custom Recipes & Balancing

- [ ] **Set up KubeJS/CraftTweaker:**
    - [ ] Create initial script files for custom recipes and events.
- [ ] **Create Inter-Mod Recipes:**
    - [ ] Ensure materials from one mod are usable in machines from another (e.g., Mekanism alloys in Immersive Engineering).
- [ ] **Adjust Existing Recipes:**
    - [ ] Increase complexity for key items (e.g., make steel production multi-step).
    - [ ] Balance ore processing yields across different machines.
- [ ] **Balance Machine Power Consumption/Production:**
    - [ ] Adjust energy requirements and outputs to fit the RF-based tiered system.

## VI. Energy System Specifics (RF)

- [ ] **Research Power Loss Mechanics:**
    - [ ] Investigate mods or KubeJS scripts that can simulate power loss over distance for RF cables.
    - [ ] Implement chosen solution for tiered energy transmission.
- [ ] **Enforce RF as Primary Energy:**
    - [ ] Disable or heavily gate EU/other energy conversions if any mods introduce them.

## VII. Space Progression

- [ ] **Select & Integrate Space Mod:**
    - [ ] Finalize choice between `Ad Astra` and `Advanced Rocketry` (or similar).
    - [ ] Integrate rocket crafting and launch into HV tier progression.
- [ ] **Plan Unique Space Resources & Challenges:**
    - [ ] Define what unique resources can only be found on the Moon/other planets.
    - [ ] Outline environmental challenges (e.g., radiation, oxygen, gravity).

## VIII. World Generation & Exploration

- [ ] **Configure Biomes O' Plenty:**
    - [ ] Adjust biome weights and features to create a cohesive world.
- [ ] **Configure YUNG's Better Structures:**
    - [ ] Ensure structures are well-integrated and provide meaningful exploration incentives.
- [ ] **Adjust Ore Generation:**
    - [ ] Make certain ores rarer or biome-specific to encourage exploration.
    - [ ] Balance overall ore availability for progression.

## IX. Quality of Life & Performance

- [ ] **Review & Configure QoL Mods:**
    - [ ] Ensure all QoL mods are configured optimally for player experience.
- [ ] **Implement Performance Enhancements:**
    - [ ] Research and add client-side performance mods (e.g., Rubidium/Oculus, FerriteCore, Canary, etc. - *verify 1.21.1 compatibility*).
    - [ ] Optimize server-side configs for stability and performance.

## X. Testing & Iteration

- [ ] **Regular Playtesting:**
    - [ ] Conduct thorough playtesting at each major progression milestone.
    - [ ] Test all custom recipes, quest objectives, and gated content.
- [ ] **Identify & Address Bottlenecks:**
    - [ ] Pinpoint areas where progression feels too slow, too fast, or unclear.
    - [ ] Balance resource sinks and gains.
- [ ] **Bug Fixing:**
    - [ ] Log and fix any mod conflicts, crashes, or unintended behaviors.

## XI. Documentation & Repository Management

- [ ] **Update `README.md`:**
    - [ ] Reflect current progress and key features.
- [ ] **Maintain `docs/` Folder:**
    - [ ] Create detailed progression documents for each tier.
    - [ ] Document custom mechanics (e.g., Blueprint system, energy loss).
- [ ] **Utilize `drafts/` Folder:**
    - [ ] Store work-in-progress KubeJS scripts, quest text drafts, etc.
- [ ] **Utilize `assets/` Folder:**
    - [ ] Add diagrams or flowcharts for complex systems (e.g., processing chains, energy networks).