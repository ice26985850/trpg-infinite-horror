# Overlord: Defense of Carne Village

> Infinite Horror TRPG Script | Format Spec v0.4 | Difficulty ★★★★★

---

## 一、基本資訊

Script Title: Overlord: Defense of Carne Village
Source Film: Overlord (オーバーロード)
Difficulty Rating: ★★★★★
Suggested Players: 3–5
Estimated Duration: 8–12 hrs / 3–4 sessions
Prerequisites: Gene Lock Stage III or higher (Stage IV recommended)
Script Type: Combat / Adventure

---

## II. Plot Summary (GM Spoilers)

### One-Line Summary

> Defend Carne Village against the Kingdom's army and survive under the protection of Lord Ainz — then strike back.

### Full Plot Background

The ruler of the Great Tomb of Nazarick — Ainz Ooal Gown — has been awake in this other world for some time. Disguised as the adventurer Momon, he established a foothold at Carne Village. But the Kingdom's nobles see this increasingly prosperous "non-human-controlled zone" as a threat, and dispatch an army to wipe it out.

The Reincarnators (輪迴者) are "recruited" by Ainz as adventurers to help defend Carne Village. In truth this is Ainz's test of them — he wants to observe how they perform under pressure, to decide whether to treat them as long-term allies... or potential threats.

The Kingdom army's main force includes the knight orders and the Sunlight Scripture — the church's elite magic unit. If they break through the village defenses, Ainz will step in personally — but that means the Reincarnators failed the test.

### Plot Structure Type

**Hybrid**: A defensive battle — three waves of Kingdom army attacks → final boss fight against the Sunlight Scripture commander.

---

## III. Main God Quest

| Field | Content |
|------|------|
| Quest Description | "Help defend Carne Village against the Kingdom army's invasion. Survive at least until reinforcements arrive (24 hours)." |
| Main Quest | Successful defense of Carne Village |
| Quest Reward | A + 10000 |
| Failure Condition | Total annihilation / Carne Village falls (Ainz will clean up the battlefield — but the Reincarnators are judged failures and erased) |
| Failure Penalty | Erasure |
| Optional Objectives | ① Earn Ainz's recognition (without letting him act personally): A1 <br>② Keep all village NPCs alive: B1 <br>③ Defeat the Kingdom army commanders (2+): C + 2000 |

---

## IV. Side Quests

| Field | Content |
|------|------|
| Side Quest ID | S-01 |
| Quest Name | Adventurer Guild Assistance |
| Trigger Condition | Travel to the nearby Adventurer Guild branch to request reinforcements |
| Quest Content | Convince the Adventurer Guild to send support (Manipulation + Social DC 4) or pay a fee (2000 RP / GM decides whether advance payment is allowed) |
| Time Limit | Before the Kingdom army's third wave |
| Reward | 1d3 adventurers join the defense + 800 |
| Relation to Main Quest | Supports the main quest — extra defensive manpower |

| Field | Content |
|------|------|
| Side Quest ID | S-02 |
| Quest Name | The Outskirts of Nazarick |
| Trigger Condition | Discover a hidden entrance to Nazarick's first floor outside the village (Perception DC 5) |
| Quest Content | Explore Nazarick's outskirts and interact with the guardians — choose to accept or refuse Ainz's "deeper test" |
| Time Limit | None |
| Reward | If accepted — gain Nazarick equipment (base defense +2 armor / DP+1 weapon / valid in this world). If refused — Ainz still respects the choice but favor drops. |
| Relation to Main Quest | Supports — gain high-tier equipment |

| Field | Content |
|------|------|
| Side Quest ID | S-03 |
| Quest Name | Division Within the Kingdom Army |
| Trigger Condition | Capture a Kingdom officer and extract intel — discover there are troops unwilling to fight |
| Quest Content | Use the intel to sow defection among dissenting units (Negotiation DC 5 / Manipulation DC 4) |
| Time Limit | Before the Kingdom army's third wave |
| Reward | 1d4 Kingdom soldiers defect and join the defense + B1 |
| Relation to Main Quest | Strongly supports the main quest — reduces the third wave's numbers and adds defensive manpower |

---

## V. World Setting

### Timeline

| T+0 hrs | Awaken at Carne Village — Ainz (disguised as Momon) gives the quest |
| T+2 hrs | Kingdom army scouts appear — first probing attack |
| T+6 hrs | Second wave: Kingdom knight main force arrives |
| T+12 hrs | Sunlight Scripture arrives — final defense |
| T+24 hrs | If defense succeeds — reinforcements arrive / if failed — Ainz personally cleans up |

### Key Locations

#### Location A: Carne Village Center (Home Base)

A simple rural farming settlement. Wooden fences are the most basic fortification. The well at the village center is the only supply source. The villagers gather fearfully near the village chief's house — they have never experienced real war.

#### Location B: The Plains Outside the Village (Battlefield)

Open plains stretch from the village edge. In the distance you can see the Kingdom army's camp tents. The plains have a few natural covers — small hills, bushes, and a shallow stream.

#### Location C: The Village Gate Fence (Defense Line)

The village's only fortification. Not sturdy — HP 100 / base defense 10 — but provides cover to defenders (base defense +2). Once the fence is breached, enemies charge straight into the village.

### World Special Rules

- **Wave System**: The Kingdom army attacks in three waves, 6 hours apart. Between waves you may repair the fence and heal.
- **Villager Morale**: The villagers' morale value (starts at 10). Each villager death -2, each breach of the defense line -2. At zero, the villagers flee en masse.
- **Ainz's Observation**: Ainz will not fight directly, but he observes the Reincarnators' performance. Outstanding performance (S-rank) grants extra rewards on clear. If forced to act (F-rank), rewards are halved.

### Main God Restrictions

- "Do not reveal Ainz's true identity to story characters (a magic-detection effect automatically blocks such dialogue)."
- "If a Reincarnator attacks innocent villagers, Ainz immediately turns hostile."

### Visual Map System

| Layer | ID | File |
|------|------|------|
| Large Map | WM-01 | `maps/OVER_WM-01.svg` |
| Exploration Map | EM-01 | `maps/OVER_EM-01.svg` |
| Combat Map | BM-01 | `maps/OVER_BM-01.svg` |
| Combat Map | BM-02 | `maps/OVER_BM-02.svg` |

---

## VII. Key Scenes

#### Scene S01: Awakening — The World Descends

| Field | Content |
|------|------|
| Scene ID | S01 |
| GM Read-Aloud Text | "You wake to find yourself lying in the corner of a wooden house. The noise outside the door snaps you alert — a black-haired young man is addressing the villagers. 'I am Momon — an adventurer. The Kingdom's army is approaching, and I need everyone who can fight to help.' He notices you're awake and nods slightly — and in his eyes you catch a glimmer of something not quite human. The Main God whispers in your ear: this 'Momon' is not human." |
| Interactive Elements | Ainz / Momon (quest briefing + provides basic equipment); villagers (may help evacuate or organize militia); village chief (provides village map and defensive-point advice); village gate fence (may be reinforced — Strength DC 3 / +30 HP to the fence) |
| Encounters | No immediate combat — guidance phase |
| Gene Lock Notes | None — guidance phase |
| Transition Condition | Obtain quest intel and decide on a course of action |

---

## VIII. Reward Settlement

#### Scene S03: Encounter — The Knight Order's Charge

| Field | Content |
|------|------|
| GM Read-Aloud Text | "Dust rises on the horizon. The thunder of hooves grows louder — the Kingdom knight order. They form a neat charge formation, lances glinting in the sun. A banner embroidered with a golden lion flies at the front. The lead knight draws his longsword: 'In the King's name — purge these non-human creatures!'" |
| Interactive Elements | Fence (must be held — may set spike traps / Agility + Trap DC 3); stream (knights must cross — may place trip-ropes on the stream bed); villager archers (if organized — deal 1d6 damage per Round) |
| Encounters | Kingdom knights ×1d6+3 (★★) + knight captain ×1 (★★★). Knights have a cavalry-charge bonus (DP+2 first Round). Horses fear fire — using fire magic can force knights off their mounts. |
| Gene Lock Notes | **Gene Lock Tip**: Gene Lock Stage III (Resolve DC 4): recommended for handling multiple targets at once — the knight captain's tactical command keeps shifting attack directions, and Gene Lock helps see through the tactics. |
| Transition Condition | Repel all knights or hold for 8 Rounds |

#### Scene S08: Final Decisive Battle — Sunlight Scripture — The Last Defense Line

| Field | Content |
|------|------|
| GM Read-Aloud Text | "The dust settles. The knights on the plains have retreated — but you know this isn't over. A sacred light illuminates the night sky — the Sunlight Scripture has arrived. White-robed mages array outside the village; their leader — a stern middle-aged man — raises a holy emblem: 'In the name of God, purify these heretics!'" |
| Interactive Elements | Village gate fence (last defense line — HP 100 / base defense 10); the central well water (holy water — effective against dark-corrosion creatures / useless against the Sunlight Scripture); houses (may serve as cover / but villagers are inside — if they collapse, villagers are hurt); Ainz (watching — only uses low-tier magic support / restores 1d4 HP each Round to a random party member) |
| Encounters | **Forced boss battle**: Sunlight Scripture commander (★★★★) ×1 + Kingdom army main force (★★★★) ×1 + Sunlight Scripture mages ×1d3 (★★★). The commander has group healing (restores 2d6 HP to all enemies every 2 Rounds) and a Holy Light Cannon (DP 9 / 4d8 radiance / ranged). The Kingdom army main force launches a formation attack (DP+2) below 50% HP. |
| Gene Lock Notes | **Gene Lock Tip**: Gene Lock Stage IV (Resolve DC 5): strongly recommended for all members. The Sunlight Scripture's Holy Light Cannon is a precise ranged attack — Stage IV grants perceptual foresight, locating the firing position one Round before the shot and gaining Dodge DC-3. |
| Transition Condition | Defeat the Sunlight Scripture commander → Kingdom army retreats → script cleared |

### Return Exchange (Script-Specific)

| Tier | Item | Cost (Side Quest + Reward Points) | Effect | Growth Path |
|------|----------|-----------------|------|----------|
| Cheap | Basic Magic (Tiers 1–3) | B + 2000 | Intellect (INT) + Arcane (magic) permanently +3; cast Tier 1–3 magic 5× per day (DP+3 / 2d8 elemental) | — |
| Cheap | Undead Servant | B + 2000 | Summon 2 low-tier undead servants (skeleton warriors, Hit Points (HP) 40) to fight alongside you | Lv1→Lv2→Lv3: skeleton → zombie → ghoul swarm |
| Cheap | Martial Arts | B + 2000 | Agility (DEX) + melee permanently +3; gain martial techniques like "Pressure" and "Flow" (2× dodge / counter per Round) | — |
| Normal | Mid-Tier Magic (Tiers 4–6) | A + 4000 | Unlock Tier 4–6 magic: area attack (DP+3 / 3d6 elemental, range 20ft) | — |
| Normal | Alchemist Class | A + 8000 | Gain "Alchemist" class levels: can craft potions (healing / buffs) and traps | Lv1→Lv2→Lv3: novice → advanced → master |
| Normal | High-Tier Magic (Tiers 7–9) | A + 4000 | Unlock Tier 7–9 magic: instant-death / space distortion (DP+4, may instant-kill DC 6 targets with HP <50%) | — |
| Expensive | Necromancer Lineage | AA + 10800 | Gain the "Necromancer" bloodline: undead command +5, immunity to negative status, dark-magic power +2 | Lv1→Lv2→Lv3: Necromancer → Lich → King of the Undead |
| Expensive | Ainz Ooal Gown's Treasure (World Item) | S + 16000 | Gain 1 "World-Class Item": game-breaking effect (e.g. "Greed and Avarice" — once per script, force-nullify 1 attack / spell) | — |
| Expensive | Super-Tier Magic | S + 8000 | Gain "Super-Tier Magic": strategic-level destruction (DP+6 / 5d10 elemental, range 60ft, once per script) | Lv1→Lv2→Lv3: single → continuous → multiple super-tier |

---

## X. Appendix

- **Maps**: `maps/OVER_WM-01.svg` ~ `OVER_BM-02.svg`
- **NPC / Enemies**: `OVER_NPC名冊.xlsx`, `OVER_敵方單位名冊.xlsx`
- **GM Memo**:

| Reward Type | Content | Points |
|----------|------|------|
| Main Quest Complete | Successful defense of Carne Village | A + 10000 |
| Optional Objective ① | Earn Ainz's recognition (S-rank) | A1 |
| Optional Objective ② | All villagers survive | B1 |
| Optional Objective ③ | Defeat 2+ commanders | C + 2000 |
| Side Quest S-01 | Adventurer reinforcements | 800 |
| Side Quest S-02 | Nazarick exploration | High-tier equipment |
| Side Quest S-03 | Subvert enemy troops | B1 |
| Kill Reward | Kingdom knight (each) | 60 |
| Kill Reward | Sunlight Scripture (each) | 250 |
| Kill Reward | Kingdom army main force | 800 |
| Special Achievement | Ainz never acts personally | 1000 |

---

> **Script Code**: OVER **Version**: v1.0 **Format Spec**: v0.4
