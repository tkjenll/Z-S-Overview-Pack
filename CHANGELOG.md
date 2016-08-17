## Changelog

>##### How to read versions:
>- A.BB.XXYY - NAME
	- A	= Game update - Sub-Classification Reset
		- **Only if** overview entity types and/or visual states are affected.
        - **Or** sub-classifications reach the max count (99).
		- Resets version sub-classifications to 0 (ex. v3.00.0000).
	- BB = Pack and Layout deployment changes
		- Addition, deletion, split, rename and adjustements.
	- XX = Preset changes amount
		- Addition, deletion, split, rename and adjustements.
		- Amounts are added up to the previous version amounts to show the current total of modifications.
	- YY = Preset updates amount
		- Types by categories and states changes.
		- Amounts are added up to the previous version amounts to show the current total of modifications.
	- NAME	= Shout out to the player(s) that provided the most feedback during the version development.

##### --- Standard Versions ---

##### Version v3.06.0523 - 118.7 - _Strawpoll results tweaks_
>1. Added a new "Z-S Full Unstylized Presets.yaml" import file.
    - It'll allow the player to save any changes to the presets without breaking the preset name entirely.
        - Will not show styling tags anymore (`<color>` & `<fontsize>`).
        - The presets will have the Default colouring.
        - The presets will have the Default font size.
    - Currently when a player saves an edited preset, the system prompts to input a name for it. The input field's character limit will cut some pre-added names.
    - The file will only be available via download from GitHub and the player will have to import it manually into the game.
        - This will avoid creating a new Mailing List and Channel due to character limits in both the Welcoming Mail and MOTD respectively.
    - We will contact CCP regarding a small update to the Overview input fields that will allow to:
        - Input longer names.
        - Input Capital letters.
        - Input styling tags (`<color>` & `<fontsize>`).
>2. Updated presets:
    - Removed Orbital:
        - "Orbital Infrastructure" from:
            - "✥ --- PvP: Basic (+NPC +Neut)"
            - "✥ --- PvP: Basic (+NPC -Neut)"
            - "✥ --- PvP: Basic (-NPC +Neut)"
            - "✥ --- PvP: Basic (-NPC -Neut)"

##### Version v3.05.0522 - 118.7 - _Bug fixing, Tweaking & Cleaning_
>1. Implemented standard nomenclatures.
>2. Renamed "Ship Bracket Row" (SBR) to "Ship Bracket Line" (SBL)
    - Updated Layout names accordingly.
>3. Changed presets:
    - Renamed "✜ --- PvE: Basic" to "✜ --- PvE: Basic (+Dro)"
    - Renamed "✪ --- Friendly: All" to "✪ --- Friendly: All (+Dro)"
    - Added "✪ --- Friendly: All (-Dro)"
    - Added "✜ --- PvE: Basic (-Dro)"
    - Removed "✜ PvE: Show Drones"
>4. Updated presets:
    - Updated NPC:
        - "Pirate NPC" on:
            - "✜ --- PvE: Basic (+Dro)"
            - "✜ --- PvE: Basic (-Dro)"
            - "✜ PvE: Anoms"
            - "✜ PvE: Mining"
            - "✜ PvE: Ratting"
            - "✥ --- PvP: Basic (+NPC +Neut)"
            - "✥ --- PvP: Basic (+NPC -Neut)"
            - "✥ --- PvP: FW"
    - Added Celestial:
        - "Force Field" to:
            - "✥ --- PvP: Basic (+NPC +Neut)"
            - "✥ --- PvP: Basic (+NPC -Neut)"
            - "✥ --- PvP: Basic (-NPC +Neut)"
            - "✥ --- PvP: Basic (-NPC -Neut)"
    - Added Charge:
        - Several to:
            - "※ D-Scan: POS (+Mod -Cel)"
    - Added Drones:
        - "Combat Drone" to:
            - "※ --- D-Scan: All"
            - "※ D-Scan: POS (+Mod +Cel)"
        - Several to:
            - "※ D-Scan: Ships (-Cel)"
    - Added Fighters:
        - All to:
            - "※ --- D-Scan: All"
            - "※ D-Scan: Ships (-Cel)"
    - Added Orbital:
        - "Orbital Infrastructure" to:
            - "✥ --- PvP: Basic (+NPC +Neut)"
            - "✥ --- PvP: Basic (+NPC -Neut)"
            - "✥ --- PvP: Basic (-NPC +Neut)"
            - "✥ --- PvP: Basic (-NPC -Neut)"
            - "※ --- D-Scan: All"
    - Added Sovereignty Structures:
        - "Sovereignty Blockade Unit" to:
            - "✥ --- PvP: Basic (+NPC +Neut)"
            - "✥ --- PvP: Basic (+NPC -Neut)"
            - "✥ --- PvP: Basic (-NPC +Neut)"
            - "✥ --- PvP: Basic (-NPC -Neut)"
    - Added Starbase:
        - "Control Tower" to:
            - "✥ --- PvP: Basic (+NPC +Neut)"
            - "✥ --- PvP: Basic (+NPC -Neut)"
            - "✥ --- PvP: Basic (-NPC +Neut)"
            - "✥ --- PvP: Basic (-NPC -Neut)"
        - Several to:
            - "※ D-Scan: POS (-Mod +Cel)"
    - Added Structure:
        - "Citadel" to:
            - "✜ PvE: Anoms"
            - "✜ PvE: Incursion"
            - "✜ PvE: Ratting"
            - "✜ PvE: Salvage/Loot"
    - Removed Asteroids:
        - All from:
            - "※ --- D-Scan: All"
            - "※ D-Scan: POS (+Mod +Cel)"
            - "※ D-Scan: POS (-Mod +Cel)"
    - Removed Celestial:
        - Several from:
            - "※ --- D-Scan: All"
            - "※ D-Scan: POS (+Mod +Cel)"
            - "※ D-Scan: POS (-Mod +Cel)"
    - Removed Charge:
        - "Survey Probe" from:
            - "※ --- D-Scan: All"
            - "※ D-Scan: POS (+Mod +Cel)"
            - "※ D-Scan: POS (-Mod +Cel)"
            - "※ D-Scan: Ships (-Cel)"
    - Removed Drones:
        - Several from:
            - "※ D-Scan: POS (+Mod +Cel)"
            - "※ D-Scan: POS (-Mod +Cel)"
    - Removed Entity:
        - All from:
            - "※ --- D-Scan: All"
            - "※ D-Scan: POS (+Mod +Cel)"
            - "※ D-Scan: POS (-Mod +Cel)"
    - Removed NPC:
        - "Mission NPC" from:
            - "※ --- D-Scan: All"
            - "※ D-Scan: POS (+Mod +Cel)"
            - "※ D-Scan: POS (-Mod +Cel)"
        - "Pirate NPC" from:
            - "※ --- D-Scan: All"
            - "※ D-Scan: POS (+Mod +Cel)"
            - "※ D-Scan: POS (-Mod +Cel)"
    - Removed Orbital:
        - "Orbital Construction Platform" from:
            - "※ D-Scan: POS (+Mod +Cel)"
            - "※ D-Scan: POS (-Mod +Cel)"
    - Removed Sovereignty Structures:
        - All from:
            - "※ D-Scan: POS (+Mod +Cel)"
            - "※ D-Scan: POS (-Mod +Cel)"
    - Removed Starbase:
        - Several from:
            - "※ D-Scan: POS (-Mod +Cel)"
    - Removed Station:
        - "Station" from:
            - "※ D-Scan: POS (+Mod +Cel)"
            - "※ D-Scan: POS (-Mod +Cel)"

##### Version v2.66.2012 - 118.6 - _Skrimokst & Parthannun's adjustements_
>1. Created two new Layouts that allow players to have single-line Player Ship Brackets instead of double-line:
	- "1 SB Row" = "1 Ship Bracket Row"
	- "2 SB Row" = "2 Ship Bracket Rows"
>2. Chaged Layouts:
	- Renamed "Z-S 6-Tab Compact Layout" to "Z-S 6-Tab Compact 2 SB Rows"
	- Renamed "Z-S 6-Tab Standard Layout" to "Z-S 6-Tab Standard 2 SB Rows"
    - Added "Z-S 6-Tab Compact 1 SB Row"
	- Added "Z-S 6-Tab Standard 1 SB Row"
	- Removed "Z-S 8-Tab Compact Layout"
	- Removed "Z-S 8-Tab Standard Layout"
>3. Changed presets:
	- Renamed "✥ --- PvP: Basic (NPC)" to "✥ --- PvP: Basic (+NPC +Neut)"
	- Renamed "✥ --- PvP: Basic (No NPC)" to "✥ --- PvP: Basic (-NPC +Neut)"
	- Renamed "※ D-Scan: POS + Mods (Cel)" to "※ D-Scan: POS (+Mods +Celes)"
	- Renamed "※ D-Scan: POS + Mods (No Cel)" to "※ D-Scan: POS (+Mods -Celes)"
	- Renamed "※ D-Scan: POS (Cel)" to "※ D-Scan: POS (-Mods +Celes)"
	- Renamed "※ D-Scan: Ships (No Cel)" to "※ D-Scan: Sips (-Celes)"
	- Split "✜ PvE: Anoms/Ratting" into:
		- "✜ PvE: Anoms"
		- "✜ PvE: Ratting"
    - Added "✥ --- PvP: Basic (+NPC -Neut)"
	- Added "✥ --- PvP: Basic (-NPC -Neut)"
>4. Updated presets:
	- Added Celestial:
		- "Force Field" to:
            - "※ D-Scan: Sips (-Celes)"
	- Added Starbase:
		- "Control Tower" to:
            - "※ D-Scan: Sips (-Celes)"
	- Added Deployable:
		- "Mobile Depot" to:
            - "✪ --- Friendly: All"
	- Removed Celestial:
		- "Asteroid Belt" from:
            - "✜ PvE: Anoms"
		- "Stargate" from:
            - "✜ PvE: Incursion"
	- Removed Deployable:
		- "Mobile Warp Disruptor" from:
            - "✜ PvE: Anoms"
            - "✜ PvE: Ratting"
		- "Mobile Cyno Inhibitor" from:
            - "✜ PvE: Anoms"
            - "✜ PvE: Ratting"
		- "Encounter Surveillance System" from:
            - "✜ PvE: Anoms"
            - "✜ PvE: Ratting"
		- "Mobile Scan Inhibitor" from:
            - "✜ PvE: Anoms"
            - "✜ PvE: Ratting"
		- "Mobile Micro Jump Unit" from:
            - "✜ PvE: Anoms"
            - "✜ PvE: Ratting"
	- Removed States:
		- "Neutral" from:
            - "✜ PvE: Incursion"
		- "No Standing" from:
            - "✜ PvE: Incursion"

##### --- Non-Standard Versions ---

##### Version v2.6.10 - 118.6 - _Kr0nK's tweaks_
>1. Updated Ship Brackets:
	- Removed "ShipName" variable (completely).
>2. Reordered Overview Columns:
	- Added "Tag" coumn:
		- Easiness of sorting and viewing of target broadcasts during fleet fights.
>3. Renamed packs:
	- "Z-S PvE Basic" to "Z-S PvE Basic Extended"
		- Corrected "Loaded" text to match the pack name.
	- "Z-S PvE Friendly" to "Z-S PvE Friendly Extended"
		- Corrected "Loaded" text to match the pack name.
>4. Changed presets:
	- Added "✥ --- PvP: Basic (No NPC)"
>5. Updated presets:
	- Added missing "Overseer NPC's" to:
		- "✥ --- PvP: Basic"
		- "✥ --- PvP: FW"
	- Removed "Starbase: Control Tower" from "✥ --- PvP: Basic":
	- Renamed "✥ --- PvP: Basic" to "✥ --- PvP: Basic (NPC)"

##### Version v2.6.00 - 118.6 - _Kithanu, Teroh & Sansh's improved Ship Brackets_
>1. Revamped Ship Brackets:
	- Condensed the information from 4 to 2 rows for legibility in ship clusters.
	- Recolored the variables for better identification.
	- Resized the variables, distinguishing from most important to insignificant (tactically speaking).
	- Removed "ShipName" variable (partially).
>2. Ranamed Tabs:
	- "Loot" to "Misc" (yellow).
	- "Misc" to "Friendly" (blue).
>3. Reorganized column order: Alliance > Corporation
>4. Changed presets:
	- Added "※ D-Scan: Pos + Mods (No Cel)"
>5. Updated presets:
	- Added missing NPC's to ALL PvE presets:
		- Overseer NPC's
		- Event NPC's
	- Renamed "※ D-Scan" presets for better understanding: (Cel stands for Celestial)
		- "※ D-Scan: Pos" to "※ D-Scan: Pos (Cel)"
		- "※ D-Scan: Pos All" to "※ D-Scan: Pos + Mods (Cel)"
		- "※ D-Scan: Ships" to "※ D-Scan: Ships (No Cel)"
	- Updated "✜ PvE: Incursion":
		- Added the most widely used and useful entities. 

##### Version v2.5.00 - 118.6 - _Logain's Modular Overhaul_
>1. Categorized preset links:
	- Replaces the split part system for a more convenient category system, where the player loads the category he/she wants/needs, then applies the final Tab Layout.
	- Made to reduce cluttering of unwanted/unneeded presets.
>2. Included changes from:
	- Version v2.3.00
	- Version v2.4.00

##### Version v2.4.00 (not released, pushed to the next version)
>1. Renamed "Brackets" presets for consistency.
>2. Renamed "Hostile" presets to "Target" for consistency.
>3. Changed presets:
    - Ranamed "✥ --- PvP: Normal" to "✥ --- PvP: Basic".
>4. Updated presets:
	- Updated "➲ Extra: Align Points":
		- Added Structure: Citadel.
	- Updated "✜ --- PvE: Basic":
		- Added Entity: Missing event NPC's.
	- Updated "✜ PvE: Salvage/Loot":
		- Added Celestial: Biomass, Secure Cargo Container, Audit Log Secure Container, Freight Container.
		- Added Deployable: Mobile Depot, Mobile Siphon Unit.
		- Added Entity: Mission Container, Event Container.

##### Version v2.3.00 (not released, pushed to the next version)
>1. Changed presets:
	- Added "⌘ --- Brackets: All":
		- More permanent solution to "Show All Brackets".
		- Works as a Collidable locator.
	- Added "✥ --- PvP: FW":
		- Derivative of "✥ --- PvP: Normal".
		- Added Entity: All FW related entities.
	- Added "※ --- D-Scan: All":
		- Combination of "※ D-Scan: Ships" and "※ D-Scan: Pos All".

##### Version v2.2.00 - 118.6 - _Deuce's design improvements_
>1. Ranamed "Finishes" to "Tab Layouts".
>2. Adjusted the sizes of both 6 & 8 Compact Layouts to fit better on smaller screens.
>3. Increased the Icon size on the presets for better legibility.
>4. Replaced the Hostile Icon for a more adequate one to fit the new sizes.

##### Version v2.1.00 - 118.6 - _Zirio's experiments_
>1. Adjusted information rows on Player Ship brackets.
>2. Updated presets:
	- Added Fighters to "Friendly: All".
	- Added Warpgates to "PvE: Incursions".
	- Added Custom Offices to "Structures".
	- Corrected typo on "PvP: Normal".

##### Version v2.0.00 - 118.6 - _Zirio's renovation_
>1. Rewrote the entirety of the code for consistency, readability, compactness and scalability.
>2. Adjusted split imports:
	- Adjusted into 4 base parts.
	- Added 4 finish parts.
>3. Added finishes:
	- Added "6 Compact Tabs".
	- Added "6 Normal Tabs".
	- Added "8 Compact Tabs".
	- Added "8 Normal Tabs".
>4. Added presets:
	- Added "PvE: Incursion".
>5. Updated presets:
	- Added Citadels to "Friendly: All".

##### Version v1.0.00 - 118.6 - _Zirio's tweaks_
>1. Manual fork from SaraShawa-Overview Pack v9.1.
	- (Export pack from the game to the overview folder, then edit the .YAML file)
>2. Simplified tabs:
	- Added tab colouring.
>3. Simplified presets:
	- Added preset colouring.
	- Added preset ideography.
>4. Created split imports:
	- Added 6 base parts.
	- Added 1 finish.
	- Added 1 optional finish.