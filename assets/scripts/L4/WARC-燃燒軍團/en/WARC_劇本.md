# Warcraft: The Burning Legion

> Infinite Horror TRPG Script | Format Spec v0.4 | Difficulty ★★★★★

---

## 一、基本資訊

Script Title: Warcraft: The Burning Legion
Source Film: Warcraft — The Burning Legion Invasion
Difficulty Rating: ★★★★★
Suggested Players: 3–5
Estimated Duration: 8–12 hrs / 3–4 sessions
Prerequisites: Gene Lock Stage III or higher (Stage IV recommended)
Script Type: Combat / Adventure

---

## II. Plot Summary (GM Spoilers)

### One-Line Summary

> Help Khadgar close the Burning Legion's portal and stop Archimonde from manifesting in Azeroth.

### Full Plot Background

The Burning Legion invades Azeroth once more. A gigantic portal torn open from the Twisting Nether endlessly pours out the demon army — felhounds, Doomguards, and Pit Lords lay waste to everything. The archmage Khadgar has gathered the last of the guardians' power, but closing the portal requires a guardian to cast at three key nodes simultaneously — and he is alone.

The Reincarnators (輪迴者) enter at this critical moment. They must help Khadgar protect the three spell-nodes from demon sabotage, while slaying enough Legion commanders to weaken the portal's energy. The guardian Medivh — though he once opened the Dark Portal — now stands with humanity, willing to use his knowledge to help close it.

But if Archimonde fully manifests through the portal — everything ends.

### Plot Structure Type

**Hybrid**: Three spell-nodes must be defended simultaneously — each node is an independent combat scene.

---

## III. Main God Quest

| Field | Content |
|------|------|
| Quest Description | "Help the archmage Khadgar close the Burning Legion's portal. Protect all three spell-nodes. Time limit: 24 hours." |
| Main Quest | Close the Burning Legion's portal |
| Quest Reward | A + 12000 |
| Failure Condition | Total annihilation / all three spell-nodes fully destroyed / Archimonde fully manifests |
| Failure Penalty | Erasure |
| Optional Objectives | ① Defeat a Pit Lord: B1 <br>② Defeat felhound commanders (cumulative 5+): C + 1500 <br>③ Help rally the orc and human allied army: B1 |

---

## IV. Side Quests

| Field | Content |
|------|------|
| Side Quest ID | S-01 |
| Quest Name | The Orcs' Honor |
| Trigger Condition | Find Grommash and help the Warsong Clan repel a felhound assault |
| Quest Content | Destroy 1d4+2 felhounds + 1 felhound commander, earn the orc tribe's trust |
| Time Limit | First 12 hours |
| Reward | 3 orc warriors join node defense + 1200 |
| Relation to Main Quest | Supports the main quest — lowers node-defense difficulty (each node +1 guard) |

| Field | Content |
|------|------|
| Side Quest ID | S-02 |
| Quest Name | The Guardian's Legacy |
| Trigger Condition | Find the Guardian's library in Medivh's Tower |
| Quest Content | Decipher the sealed ancient texts (Intellect + Occultism DC 4, 2 checks) to find the spell that accelerates the portal's closure |
| Time Limit | Before the main quest ends |
| Reward | Portal closure time halved (from 10 Rounds → 5 Rounds) + B1 |
| Relation to Main Quest | Greatly supports the main quest — shortens the boss battle duration |

| Field | Content |
|------|------|
| Side Quest ID | S-03 |
| Quest Name | The Demon's True Name |
| Trigger Condition | Capture and interrogate a felhound commander (requires at least 1 successful Intimidation DC 4 or Negotiation DC 4) |
| Quest Content | Wrench the Pit Lord's true name from the demon — it can be used to weaken him |
| Time Limit | Before encountering the Pit Lord |
| Reward | Pit Lord AC-3 / DP-2 + 600 |
| Relation to Main Quest | Supports the main quest — lowers the Pit Lord battle difficulty |

---

## V. World Setting

### Timeline

| T+0 hrs | Awaken at the ruins of Dalaran — Khadgar is preparing the portal-closure ritual |
| T+3 hrs | First spell-node begins — felhound vanguard attacks |
| T+6 hrs | Medivh arrives — provides the acceleration spell |
| T+12 hrs | Pit Lord appears — second node defense battle |
| T+18 hrs | Archimonde begins manifesting through the portal — third node final defense |
| T+24 hrs | Portal fully opens — quest failed |

### Key Locations

#### Location A: Ruins of Dalaran (Start Point / First Node)

The once city of magic is now half-ruined. Khadgar carves a gigantic sealing rune into the magic array at the city center. Around it burn buildings and scattered pages of spellbooks.

#### Location B: Medivh's Tower (Second Node)

A lonely stone tower rises on the wasteland. Its top observatory overlooks the full panorama of the portal. Medivh prepares the second sealing array here.

#### Location C: Dark Portal Ruins (Third Node / Final)

The portal ruins that once linked to Draenor — now the Burning Legion uses the same spatial fissure to build its invasion channel. The Twisting Nether's light streams from the rift into this world.

### World Special Rules

- **Portal Energy**: Every 6 hours elapsed, Legion reinforcement strength +1 (initial ★★ → final ★★★★).
- **Node Defense**: Each node requires 10 Rounds of chanting. Being attacked interrupts it — each interrupted Round sets progress back 2 Rounds.
- **Medivh's Sacrifice**: If the situation is critical, Medivh may sacrifice himself to fully close the portal — but this costs the party its wise guidance.

### Main God Restrictions

- "Do not reveal the existence of the Main God Space to story characters."
- "If all three spell-nodes fall, the portal opens irreversibly."

### Visual Map System

| Layer | ID | File |
|------|------|------|
| Large Map | WM-01 | `maps/WARC_WM-01.svg` |
| Exploration Map | EM-01 | `maps/WARC_EM-01.svg` |
| Combat Map | BM-01 | `maps/WARC_BM-01.svg` |
| Combat Map | BM-02 | `maps/WARC_BM-02.svg` |

---

## VII. Key Scenes

#### Scene S01: Awakening — The World Descends

| Field | Content |
|------|------|
| Scene ID | S01 |
| GM Read-Aloud Text | "The acrid smell of sulfur is the first thing to hit your nostrils. You lie amid rubble — the former Dalaran Academy of Magic, now half-ruined. In the sky, a massive green rift is expanding — that is the Burning Legion's portal. A white-haired old man stands before you, the tip of his staff glowing faint blue. 'Thank the gods — I thought we'd be too late. I am Khadgar. We don't have much time.'" |
| Interactive Elements | Khadgar (quest briefing + intel on the three node locations); magic array (may help carve it — Intellect + Occultism DC 3 / +20 HP to the node); surrounding ruins (search yields magic potions ×3) |
| Encounters | No immediate combat — guidance phase |
| Gene Lock Notes | None — guidance phase |
| Transition Condition | Obtain quest intel and decide on a course of action |

---

## VIII. Reward Settlement

#### Scene S03: Encounter — Node Defense — Pit Lord Assault

| Field | Content |
|------|------|
| GM Read-Aloud Text | "No sooner is the second node laid than a deep roar sounds from the sky. A gigantic figure squeezes through the portal — taller than any building, wreathed in green hellfire. A Pit Lord. He raises his gigantic warhammer and bellows at the node. The ground trembles beneath your feet." |
| Interactive Elements | Node (HP 150 / base defense 14 — must be protected); surrounding magic towers (may topple to knock down the Pit Lord for DP 10 / Strength DC 5); Khadgar (provides ranged fire support — DP 8 arcane to 1 enemy per Round) |
| Encounters | Pit Lord (★★★★) ×1 + felhounds ×1d4. The Pit Lord releases demon flame every 2 Rounds (DP 9 / range 30ft / 4d6 fire). |
| Gene Lock Notes | **Gene Lock Tip**: Gene Lock Stage III (Resolve DC 4): recommended for locating the Pit Lord's attack blind spot — gain a 1-Round invincibility window while the warhammer charges. |
| Transition Condition | Protect the node for 10 Rounds or defeat the Pit Lord |

#### Scene S08: Final Decisive Battle — Archimonde Descends

| Field | Content |
|------|------|
| GM Read-Aloud Text | "The third node — and the last hope. Khadgar and Medivh begin the final sealing chant together. But just then the portal shudders violently — a massive arm wreathed in flame extends from the rift. Archimonde. The Defiler. He is pulling himself from the Twisting Nether into this world. His eyes lock onto you — onto the spell-node." |
| Interactive Elements | Node (HP 200 / must be protected within 10 Rounds — completing S-02 shortens to 5 Rounds); Medivh's barrier (grants the node temporary invincibility / lasts 3 Rounds / usable once); Khadgar's array (if a party member helps guide the energy — Intellect + Occultism DC 4 speeds chanting by 0.5 Round per Round) |
| Encounters | **Forced boss battle**: Archimonde (★★★★★+) — not-yet-fully-manifested state. HP 200 (true body) / DP 12. Every 3 Rounds the Legion summons reinforcements. Must protect the node before the portal fully opens. After Archimonde fully manifests: HP = 300 / DP = 14 / auto-attacks each Round. |
| Gene Lock Notes | **Gene Lock Tip**: Gene Lock Stage IV (Resolve DC 5) is the minimum requirement. Archimonde's Finger of Death is an instant-death-level threat — Stage IV lets you sense the mana coalescing 1 Round before casting, gaining DC-3 Reflex to evade. |
| Transition Condition | Portal fully closed → script cleared |

### Return Exchange (Script-Specific)

| Tier | Item | Cost (Side Quest + Reward Points) | Effect | Growth Path |
|------|----------|-----------------|------|----------|
| Cheap | Demon Blood | B + 2000 | Drink demon blood: Strength (STR) +3, Hit Points (HP) +30, at the cost of -1 Sanity, and gain 1×/day Demon Charge (DP+2) | Lv1→Lv2→Lv3: first drink → demonized → half-demon |
| Cheap | Orc Warrior Training | B + 2000 | Strength (STR) + melee permanently +3; Berserk (2× per battle, Strength +3 / 3 Rounds) | — |
| Cheap | Druid Nature Magic | B + 2000 | Gain druid nature magic: healing (recover Hit Points (HP) 15 / Round), root binding (DP+3, bind 1d3 Rounds) | — |
| Normal | Fel Magic | A + 4000 | Unlock "Fel": green-flame attack (DP+3 / 2d8 fel, may corrupt terrain) | Lv1→Lv2→Lv3: minor fel → fel burn → demon form |
| Normal | The Holy Light | A + 4000 | Gain "Holy Light": healing and undead/demon banishment (DP+3 vs undead / demons), Will (Charisma (CHA)) +2 | — |
| Normal | Shadow Magic | A + 4000 | Gain Shadow Bolt / Shadow Cloak: DP+3 shadow damage, Stealth (Perception (WIS) DC-2) | — |
| Expensive | Illidan's Eyes | S + 9600 | Gain the "Demon Hunter" eyes: full-field perception, demon true-name sense, shadow / fel power +2 | Lv1→Lv2→Lv3: blind → demon eyes → Demon Hunter awakening |
| Expensive | Frostmourne | S + 8000 | Gain the "Frostmourne" runeblade: soul devour (DP+5, heal Hit Points (HP) 15 on hit), control undead | — |
| Expensive | Flame of Sargeras | S + 8000 | Gain Sargeras's genesis-level flame: devastating strike (DP+6 / 5d10 arcane fire, range 50ft) | Lv1→Lv2→Lv3: spark → blaze → Titan's Flame |

---

## X. Appendix

- **Maps**: `maps/WARC_WM-01.svg` ~ `WARC_BM-02.svg`
- **NPC / Enemies**: `WARC_NPC名冊.xlsx`, `WARC_敵方單位名冊.xlsx`
- **GM Memo**:

| Reward Type | Content | Points |
|----------|------|------|
| Main Quest Complete | Close the portal | A + 12000 |
| Optional Objective ① | Defeat the Pit Lord | B1 |
| Optional Objective ② | Defeat 5+ felhound commanders | C + 1500 |
| Side Quest S-01 | Orcs' honor | 1200 |
| Side Quest S-02 | Guardian's legacy | B1 |
| Side Quest S-03 | Demon's true name | 600 |
| Kill Reward | Felhound (each) | 120 |
| Kill Reward | Pit Lord | 1000 |
| Kill Reward | Archimonde (unmanifested) | 2000 |
| Special Achievement | All three nodes never hit | 800 |

---

> **Script Code**: WARC **Version**: v1.0 **Format Spec**: v0.4
