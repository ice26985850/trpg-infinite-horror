# Half-Life: Black Mesa Escape

> Infinite Terror TRPG Script | Format Spec v0.4 | Difficulty ★

---

## 一、基本資訊

Script Title: Half-Life: Black Mesa Escape
Source Film: Half-Life (1998)
Difficulty Rating: ★
Suggested Players: 3–5
Estimated Duration: 3–4 hrs / 1–2 sessions
Prerequisites: None (suitable for newcomers to the Reincarnation cycle)
Script Type: Survival / Escape

---

## II. Story Overview (GM Only)

### One-Line Summary

> Deep within the Black Mesa Research Facility in New Mexico, a resonance cascade experiment tears open a dimensional rift. Alien creatures from the border world Xen invade, and the military seals the facility to eliminate all witnesses. The Reincarnators must traverse labs, ventilation ducts, and military blockades to escape alive.

### Full Story Background

The Black Mesa resonance cascade disaster occurs exactly as the Reincarnators enter. The facility instantly becomes an alien hunting ground and a target of the military's cover-up purge. The only way out: cross the chaotic facility, avoid the Marines' indiscriminate sweep, and reach the surface evacuation point before the full nuclear detonation.

### Story Structure Type

**Hybrid:** free exploration of the lab area in the first half to gather weapons and intel, then act-by-act progression crossing the military blockade in the second half.

---

## III. Lord God Mission

| Field | Content |
|------|------|
| Mission Brief | "Before Black Mesa is destroyed by the nuke, reach the surface Lambda Lab evacuation point. Time limit: 24 hours." |
| Main Mission | Escape Black Mesa within 24 hours and reach the Lambda Lab evacuation point |
| Mission Reward | D+1200 |
| Failure Condition | Total party wipe / failing to reach the evacuation point within 24 hours / captured by the military |
| Failure Penalty | Erasure |
| Optional Objectives | ① Rescue scientists: +150 each, max 5 <br>② Close the dimensional rift: INT + Tech, DC4; success grants D1 |

---

## IV. Side Quests

| Field | Content |
|------|------|
| Side Quest ID | S-01 |
| Quest Name | Particle Accelerator Restart |
| Trigger | Enter the anomalous materials lab |
| Objective | Restart the particle accelerator to stabilize the dimensional rift (INT + Tech, DC4), stopping further alien invasion |
| Time Limit | Within 4 hours |
| Reward | 800 |
| Relation to Main Mission | Supportive — reduces subsequent alien encounters by 50% |
| Notes | Must first clear the headcrabs and barnacles in the lab |

| Field | Content |
|------|------|
| Side Quest ID | S-02 |
| Quest Name | Armory Unlock |
| Trigger | Arrive at the security center computer room |
| Objective | Hack the security system (INT + Computer, DC3) to open the armory and obtain military weapons |
| Time Limit | None |
| Reward | 500 |
| Relation to Main Mission | Supportive — obtain heavy-fire weapons |
| Notes | Marines patrol the armory. MP5 ×2 (1d8), Shotgun ×1 (2d6) |

| Field | Content |
|------|------|
| Side Quest ID | S-02 |
| Quest Name | Trapped Scientist Squad |
| Trigger | Explore the materials science lab |
| Objective | A squad of 3 scientists is trapped in the observation room; the door lock is broken and headcrabs are in the vents. Clear 5 headcrabs and repair the door lock |
| Time Limit | Scientists have 2 hours of oxygen left |
| Reward | 600 |
| Relation to Main Mission | Supportive — +3 scientists counted toward optional ① |
| Notes | Led by Dr. Rosenberg, who can provide shortcut info about the facility |

---

## V. World Setting

### Timeline

| Time | Event |
|------|------|
| T+0 | Resonance cascade. Reincarnators awaken in the test lab observation room |
| T+2 | Military arrives, seals all exits |
| T+6 | Alien invasion intensifies, multiple cave-ins |
| T+12 | Marines begin indiscriminate cleanup |
| T+18 | Military declares "full decontamination" — prepares to detonate the nuke |
| T+24 | Nuke detonation countdown hits zero |

### Key Locations

#### Location: Observation Room (Starting Point)

| Field | Content |
|------|------|
| Location Name | Observation Room (Starting Point) |
| Environment | Test lab observation room; monitors show the test chamber in chaos — green lightning, floating debris. Alarms scream. |
| Explorable | HEV Suit ×1 (+2 base DEF, built-in flashlight), first-aid station |
| Possible Encounter | 1 headcrab in the corridor |
| Connections | Leads to test chamber → Sector B labs |
| Map Ref | EM-01 |

#### Location: Anomalous Materials Lab

| Field | Content |
|------|------|
| Location Name | Anomalous Materials Lab |
| Environment | A massive ring-shaped particle accelerator occupies the entire space. Strange sounds echo from beneath the grating floor. |
| Explorable | Particle accelerator console (S-01), toolbox (crowbar ×1, 1d6) |
| Possible Encounter | 3 headcrabs + 2 barnacles (ceiling) |
| Connections | Leads to Sector C materials lab, Sector D security center |
| Map Ref | EM-01 |

#### Location: Materials Science Lab

| Field | Content |
|------|------|
| Location Name | Materials Science Lab |
| Environment | The observation room glass is shattered; scientists are trapped inside. Headcrab hisses come from the vents. |
| Explorable | High-energy laser (1d10 fire), S-03 trigger point |
| Possible Encounter | 5 headcrabs in the vents |
| Connections | Returns to anomalous materials lab |
| Map Ref | EM-01 |

#### Location: Security Center

| Field | Content |
|------|------|
| Location Name | Security Center |
| Environment | A monitoring room; displays show every sector of the facility. Marines are advancing. |
| Explorable | Computer terminal (S-02), armory door (requires hacking), surveillance system |
| Possible Encounter | 2 patrolling Marines (M4 rifle, 1d10) |
| Connections | Leads to the start of the evacuation route |
| Map Ref | BM-01 |

#### Location: Lambda Lab (Evacuation Point)

| Field | Content |
|------|------|
| Location Name | Lambda Lab (Evacuation Point) |
| Environment | Deep within the high-energy physics lab, a massive dimensional portal emits green light. It is the door to Xen — and the way home. |
| Explorable | Portal control system, final supply crate |
| Possible Encounter | 4 Marines block the portal; 3 barnacles on the ceiling |
| Connections | Enter the portal → cleared |
| Map Ref | BM-02 |

### World Special Rules

- **Resonance Field:** Some areas have a resonance field (green flash); entering requires an END check DC3 to avoid 2d6 radiation damage.
- **Ventilation System:** The facility is threaded with ventilation ducts (AGI + Stealth, DC2) that bypass most enemies.
- **Scarce Supplies:** The facility's standard weapons are limited (crowbar, pistol); heavy weapons must be captured from Marines.
- **Structural Collapse:** After T+12, each hour has a 20% chance of a sector cave-in (AGI + Athletics, DC3, to avoid).

### Lord God Restrictions

- "Forbidden to reveal the existence of the Lord God Space to story characters."
- "This world forbids tech items from after 1998."
- "Killing an innocent scientist costs 200 each."

### Visual Map System

| Tier | ID | Content | File |
|------|------|------|------|
| World Map | WM-01 | Black Mesa facility floor plan and surrounding area, with evacuation route | `maps/HL_WM-01.svg` |
| Exploration Map | EM-01 | Exploration map of Sectors B–D, with each lab and the security center | `maps/HL_EM-01.svg` |
| Combat Map | BM-01 | Security center armory (14×10) | `maps/HL_BM-01.svg` |
| Combat Map | BM-02 | Lambda Lab portal area (12×8) | `maps/HL_BM-02.svg` |

---

## VI. Characters & Enemy Units (Managed Separately in Excel)

> ⚠️ For NPC and enemy unit data, see the following standalone Excel files:
> - **NPC Roster**: `HL_NPC名冊.xlsx`
> - **Enemy Unit Roster**: `HL_敵方單位名冊.xlsx`
>
> Both Excel files contain two sheets — "Roster" and "Blank Template" — with the first column reserved for the character art.

---

## VII. Key Scenes

### Scene Structure

Phase One: free exploration to gather supplies and intel. Phase Two: act-by-act progression of key missions.

---

#### Scene S01: Resonance Disaster

| Field | Content |
|------|------|
| Scene ID | S01 |
| Scene Name | Resonance Disaster |
| Trigger | Script start |
| Environment | "The test chamber glass suddenly shatters. Green arcs burst from the particle accelerator's core, and agonized screams echo from the lab corridor. Your watch lights up: '24 hours. Lambda Lab.' Footsteps — not human — skitter from the vent." |
| Interactive Elements | HEV suit (+2 base DEF), first-aid station, communicator to contact other scientists |
| Encounter | 1 headcrab in the corridor. Firing draws 3 more. |
| Gene Lock | None (guidance phase) |
| Branch Options | Explore immediately → S02; check communicator → obtain facility map |
| Transition Condition | Leave the observation room |

#### Scene S02: Anomalous Materials

| Field | Content |
|------|------|
| Scene ID | S02 |
| Scene Name | Anomalous Materials |
| Trigger | Enter the anomalous materials lab |
| Environment | "The accelerator emits an unstable hum. The control panel blinks red. You see a scientist's corpse hanging from the ceiling — not hanged, but caught by some mucus-covered tongue." |
| Interactive Elements | Console (S-01), toolbox, security door (requires engineer password) |
| Encounter | 3 headcrabs + 2 barnacles (ceiling, 20 ft high) |
| Gene Lock | Barnacles require stealth bypass or ranged kill. Gene Lock Stage 1 (RES DC2) grants +2 hit DP |
| Branch Options | To materials lab → S03; to security center → S04 |
| Transition Condition | Choose direction |

#### Scene S03: Scientist Rescue

| Field | Content |
|------|------|
| Scene ID | S03 |
| Scene Name | Scientist Rescue |
| Trigger | Arrive at the materials lab |
| Environment | "The observation room glass is shattered. Through the crack you see three scientists — they've barricaded the vent with desks, but headcrabs are squeezing in through the joints." |
| Interactive Elements | Dialogue with Dr. Rosenberg, console, vent entrance |
| Encounter | 5 headcrabs in the vents. Quick action allows a preemptive strike. |
| Gene Lock | Enclosed-space combat: Gene Lock Stage 1 (RES DC2), +2 Attack DP, +3 Initiative |
| Branch Options | Rescue all → gain shortcut info and +3 scientists; fail → lose everything |
| Transition Condition | Complete rescue or choose to abandon |

#### Scene S04: The Armory Fight

| Field | Content |
|------|------|
| Scene ID | S04 |
| Scene Name | The Armory Fight |
| Trigger | Arrive at the security center |
| Environment | "Surveillance screens show Marines advancing floor by floor. A soldier's voice comes over the communicator: 'Target is to eliminate all witnesses — including staff.' They're here." |
| Interactive Elements | Computer terminal (S-02 hack), surveillance system, armory |
| Encounter | 2 patrolling Marines (M4, base DEF 12, HP 25), 60% chance of reinforcements arriving within 1 round |
| Gene Lock | High Marine threat: Gene Lock Stage 1 (RES DC3), +3 Initiative, +2 damage |
| Branch Options | Frontal assault → high risk but can capture weapons; stealth bypass → save ammo |
| Transition Condition | Obtain armory supplies |

#### Scene S05: Military Blockade

| Field | Content |
|------|------|
| Scene ID | S05 |
| Scene Name | Military Blockade |
| Trigger | On the way to the Lambda Lab |
| Environment | "Concrete roadblocks and machine-gun emplacements appear at the corridor corner. 'This is a restricted zone! Anyone who approaches will be shot on sight!'" |
| Interactive Elements | Roadblock (clearable with grenades), vent detour, elevator shaft |
| Encounter | 4 Marines (2 rifle + 2 shotgun), 1 auto gun turret (3d6/round) |
| Gene Lock | Gun turret needs quick handling: Gene Lock Stage 1 (RES DC3), +3 AGI check DP |
| Branch Options | Frontal breakthrough → fastest but high casualty risk; vent stealth → 2 hours but safe; elevator shaft → dangerous but may reach directly |
| Transition Condition | Break through the blockade |

#### Scene S06: Nuke Countdown

| Field | Content |
|------|------|
| Scene ID | S06 |
| Scene Name | Nuke Countdown |
| Trigger | Announced over the broadcast system after T+18 |
| Environment | "Facility broadcast: 'Emergency notice. Nuclear device activated, detonation in T-6 hours. All personnel evacuate immediately.' Concrete begins falling from the ceiling." |
| Interactive Elements | Evacuation route signs, final supply crate, emergency generator |
| Encounter | After T+18, each hour 20% chance of sector cave-in (3d6 damage, DC3 to avoid) + patrolling aliens |
| Gene Lock | Time pressure and environmental threat: under high stress, Gene Lock Stage 2 (RES DC4), +2 to all checks but 1d4 mental damage per round |
| Branch Options | Full sprint → may miss supplies; planned route → controlled but time-consuming |
| Transition Condition | Reach the Lambda Lab |

#### Scene S07: The Portal Fight

| Field | Content |
|------|------|
| Scene ID | S07 |
| Scene Name | The Portal Fight |
| Trigger | Arrive at the Lambda Lab |
| Environment | "A massive circular portal emits green light. But 4 Marines stand before the door — their guns trained on the gateway. At least 3 barnacles hang from the ceiling." |
| Interactive Elements | Portal control (INT + Tech, DC3, to activate), cover (lab equipment) |
| Encounter | 4 Marines + 3 barnacles. If the rift was closed earlier (S-01), aliens reduced by 2 |
| Gene Lock | Final battle: Gene Lock Stage 1 (RES DC3), +2 Attack DP, +3 Initiative. Side effect: 2d4 mental damage |
| Branch Options | Wipe all enemies → enter portal step by step; activate portal then sprint → may take hits but fastest |
| Transition Condition | Cross the portal, script cleared |

---

## VIII. Multi-Team Competition Rules

> This script does not involve multi-team competition. This section is intentionally left blank.

---

## IX. Reward Settlement

| Reward Type | Content | Points |
|----------|------|------|
| Main Mission | Escape Black Mesa within 24 hours, reach the Lambda Lab evacuation point | D+1200 |
| Optional Objectives | ① Rescue scientists: +150 each, max 5 <br>② Close dimensional rift: INT + Tech, DC4, success grants D1 | 800–1500 |
| Side S-01 | Side Quest One | 500 |
| Side S-02 | Side Quest Two | 500 |
| Side S-03 | Side Quest Three | 800 |
| Kill Reward | Normal enemy (each) | 15 |
| Kill Reward | Elite / Boss | 50 |
| Exploration Reward | Discover all key locations | 100 |
| Special Achievement | Perfect Clear | 300 |
| Special Achievement | Special Achievement | 200 |
| Roleplay | At GM discretion | 0–300 |

### Theoretical Maximum Yield

> Main: D×1 + 1200
> Side total: ~2200
> Kill rewards: ~800
> Exploration / achievement / roleplay: ~800
>
> = D + ~5000

### Return Exchange (Script-Exclusive)

| Tier | Exchange Item | Cost (Side + Reward Points) | Effect | Growth Path |
|------|----------|----------------------|------|----------|
| Cheap | HEV Armor Operation | D+500 | Skill: pilot HEV powered armor, +2 base DEF, +5 max HP | — |
| Cheap | Xen Ecology Knowledge | D+500 | Skill: +2 Investigation checks, identify Xen creature weaknesses | — |
| Cheap | Headcrab Parasite Resistance | D+500 | Modification (passive): permanently immune to headcrab parasitism, +3 headshot-save DC | — |
| Normal | Gravity Gun | C+1000 | Item: manipulate "zero-point energy" to lift/launch heavy objects (2d6 STR damage) | — |
| Normal | Dimensional Teleport Knowledge | C+1000 | Skill: decipher teleport devices, plan cross-dimensional routes (WIS +2) | — |
| Normal | Gordon-Class Engineering Bloodline | C+1000 | Bloodline: physicist constitution, +2 to all science/engineering checks, +2 will in crisis | — |
| Expensive | Time Manager's Favor | C+2000 | Privilege (passive): gain G-Man's gaze, once per battle "freeze time" for 2 rounds (self only) | — |

---

## X. Appendix

- **Maps:** See `maps/` directory: `HL_WM-01.svg`, `HL_EM-01.svg`, `HL_BM-01.svg`, `HL_BM-02.svg`
- **Special Rules Supplement:** — **Resonance Field:** some areas have a resonance field (green flash); entering requires END check DC3 to avoid 2d6 radiation damage.
- **Ventilation System:** the facility is threaded with ventilation ducts (AGI + Stealth, DC2) that bypass most enemies.
- **Scarce Supplies:** the facility's standard weapons are limited (crowbar, pistol); heavy weapons must be captured from Marines.
- **Structural Collapse:** after T+12, each hour has a 20% chance of a sector cave-in (AGI + Athletics, DC3, to avoid)...
- **GM Memo:**
 - **Common Stuck Points:** Players may be overly cautious. Solution — apply time pressure or have NPCs actively request help.
 - **Difficulty Up:** Enemy count ×1.5, key check DC +1.
 - **Difficulty Down:** Enemy count ×0.7, key check DC -1.
 - **Unconventional Player Actions:** If players adopt unconventional strategies, assess reasonableness and apply corresponding consequences.
- **Reference Material:** Half-Life (1998) and related source material.

---

> **Script Code:** HL
> **Version:** v1.0
> **Format Spec:** v0.4
