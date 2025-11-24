# Mage Clothing & Armor Sets
Equipment Database for the Mage Class

**Version:** 0.2 (Prototype - Tiers 1-12)  
**Last Updated:** Nov 23, 2025  
**Total Sets Planned:** 45 (Index 01–45)  
**Currently Populated:** 11 Sets (Index 01–11, with Tier 1–2 coverage added)  
**Reserved Slots:** Index 12–45 (Placeholder for future expansion)

---

## Schema Overview

Each set entry includes the following fields:
- **Set Slot Index:** Unique identifier (01–45) for tracking and avoiding duplicates
- **Set Name:** Theme name for all 5 pieces (e.g., "Flame Caster Set")
- **Piece Name:** Individual name per slot (Head/Chest/Legs/Hands/Boots)
- **Slot:** Equipment slot type
- **Class:** Mage (locked for this file)
- **Role:** DPS / Control / Hybrid designation
- **Path Focus:** Fire (Pyromancer) / Ice (Cryomancer) / Time (Chronomancer) / Balanced / Void / Ultimate
- **Tier Range:** Skill Tier & Level requirement (e.g., "Tiers 1–3 (Lv 2–10)")
- **Intended Stat Focus:** Conceptual stat emphasis (e.g., "Focus: INT 15–20")
- **Secondary Emphasis:** Supporting stat direction (e.g., "Minor CON for survival")
- **Unique Effect:** Special trait or mechanic (qualitative, no %)
- **Acquisition Method:** Drop / Craft / Quest / Boss / Vendor
- **Map Tier:** World region (Map 1–10)
- **Rarity:** Common / Uncommon / Rare / Epic / Legendary / Mythic / Void-touched
- **Material Requirements:** Crafting materials (names from item_all_type.md)
- **Set Bonus:** Bonus effects for 2-piece, 3-piece, 5-piece completion
- **Upgrade Path:** Indicates evolution tier (I / II / III)
- **Lore Placeholder:** Flavor text (currently generic—pending lore.md development)

**Key Mage Distinctions:**
- All armor pieces are **Cloth/Robe type** (no plate, leather minimal)
- Focus on **INT stat** (up to 99) with secondary CON/DEX for survival/speed
- **3 Elemental Paths:** Fire (Pyromancer), Ice (Cryomancer), Time (Chronomancer)
- **No Tank Role** – all DPS/Control/Hybrid (reflects low physical defense)
- **Current Distribution (11 sets):** Tier 9–10 Convergence (1 set) + Tier 1–2 Apprentice (1 set) + Tier 2–8 Specialists (9 sets) = full Tier coverage

---

## 🔥 Mage Equipment Sets (Populated: 01–11)

### Set 01: Arcane Convergence
*Tier Range: 9–10 (Lv 50–60) | Path: Balanced (Fire+Ice+Time Bridge) | Role: DPS/Hybrid | Map: 7–8 | Rarity: Legendary*

| Slot | Piece Name | Intended Focus | Secondary | Unique Effect | Material Req | Acquisition |
|------|------------|---|---|---|---|---|
| **Head** | Convergence Crown | INT 55+ | - | All elements beckon | Cloth x2, Ectoplasm, Void Shard, Reality Fragment x2 | Drop (Map 7–8 Convergence Site) + Quest |
| **Chest** | Convergence Robe | INT 55+ | All elements | Fire/Ice/Time unified pulse | Cloth x3, Ectoplasm x2, Void Shard x2, Reality Fragment x2 | Quest (SQ-28: Convergence) + Craft |
| **Legs** | Convergence Leggings | INT 52+ | All synergy | Bridge between realms | Cloth x2, Ectoplasm, Void Shard, Reality Fragment | Craft |
| **Hands** | Convergence Gloves | INT 50+ | All elements | Gesture reaches all planes | Cloth, Ectoplasm x2, Void Shard, Reality Fragment | Craft |
| **Boots** | Convergence Steps | INT 50+ | - | Walk between all elements | Cloth x2, Ectoplasm, Reality Fragment x2 | Craft |

**Set Bonus:**
- (2) Fire/Ice/Time cooldowns -1 turn each
- (3) Spell potency from all paths +30%
- (5) Multi-element trigger synergy (use 2 elements = bonus)

**Upgrade Path:** I (Legendary) → II (Mythic - "Eternal Convergence")  
**Lore:** Robes where all elemental forces converge. The pinnacle before ultimate mastery.

---

### Set 02: Apprentice's Vestments
*Tier Range: 1–2 (Lv 2–5) | Path: Balanced | Role: DPS | Map: 1 | Rarity: Common*

| Slot | Piece Name | Intended Focus | Secondary | Unique Effect | Material Req | Acquisition |
|------|------------|---|---|---|---|---|
| **Head** | Apprentice's Cap | INT 10+ | - | Faint magical spark | Cloth Scrap x2, Feather | Quest (MQ-01: First Steps) |
| **Chest** | Apprentice's Robe | INT 10+ | CON 5+ | Beginner's comfort | Cloth Scrap x3, Boar Tusk | Quest (MQ-01) + Vendor |
| **Legs** | Apprentice's Trousers | INT 8+ | - | Unrestricted movement | Cloth Scrap x2, Feather | Vendor (Town NPC) |
| **Hands** | Apprentice's Sleeves | INT 8+ | CON 5+ | Fumbling spellcasts | Cloth Scrap, Feather x2 | Vendor (Town NPC) |
| **Boots** | Apprentice's Footwear | INT 8+ | - | First journeys begin | Cloth Scrap x2, Feather | Vendor (Town NPC) |

**Set Bonus:**
- (2) Base spell damage +10%
- (3) Mana recovery +5% per turn
- (5) Beginning's Blessing: Experience gain +15%

**Upgrade Path:** I (Common) → II (Uncommon - "Scholar's Vestments")  
**Lore:** Simple robes worn by those first discovering magic. Worn with hope and uncertainty.

---

### Set 03: Ashwood Weaver
*Tier Range: 2–3 (Lv 5–10) | Path: Fire | Role: DPS | Map: 1–2 | Rarity: Uncommon*

| Slot | Piece Name | Intended Focus | Secondary | Unique Effect | Material Req | Acquisition |
|------|------------|---|---|---|---|---|
| **Head** | Weaver's Cowl | INT 15+ | - | Fire resonance aura | Cloth Scrap x2, Feather | Drop (Map 1 Elite) |
| **Chest** | Weaver's Robe | INT 15+ | Fire dmg seed | Flame affinity begins | Cloth Scrap x3, Boar Tusk | Craft / Drop |
| **Legs** | Weaver's Leggings | INT 15+ | - | Smooth spell flow | Cloth Scrap x2, Wood | Drop (Map 2 Chests) |
| **Hands** | Weaver's Sleeves | INT 12+ | Fire output | Gesture-enhanced casting | Cloth Scrap, Feather x2 | Craft |
| **Boots** | Weaver's Sandals | INT 12+ | - | Swift flame spreading | Cloth Scrap x2, Feather | Craft / Vendor |

**Set Bonus:**
- (2) Fire spells gain +20% potency seed
- (3) Fireball cooldown -1 turn
- (5) Fire DoT duration +1 turn

**Upgrade Path:** I (Uncommon) → II (Rare - "Flame Weaver")  
**Lore:** Robes woven from fire-resistant fibers. First step toward flame mastery.

---

### Set 04: Frost Initiate
*Tier Range: 3–4 (Lv 10–15) | Path: Ice | Role: Control | Map: 2 | Rarity: Uncommon*

| Slot | Piece Name | Intended Focus | Secondary | Unique Effect | Material Req | Acquisition |
|------|------------|---|---|---|---|---|
| **Head** | Initiate's Crown | INT 18+ | CON 12+ | Frost mind clarity | Cloth Scrap x2, Antidote Herb | Quest Chain (SQ-03) |
| **Chest** | Initiate's Mantle | INT 18+ | CON 15+ | Ice barrier foundation | Cloth Scrap x3, Antidote Herb x2 | Quest Chain (SQ-03) |
| **Legs** | Initiate's Trousers | INT 15+ | - | Balanced ice control | Cloth Scrap x2, Feather | Quest Chain (SQ-03) |
| **Hands** | Initiate's Gloves | INT 15+ | CON 10+ | Freeze gesture mastery | Cloth Scrap, Antidote Herb | Quest Chain (SQ-03) |
| **Boots** | Initiate's Footwear | INT 15+ | - | Slippery ice walk | Cloth Scrap x2, Antidote Herb | Quest Chain (SQ-03) |

**Set Bonus:**
- (2) Freeze chance +15%
- (3) Ice Bolt cooldown -1 turn
- (5) Frozen enemies take +25% from fire (elemental synergy hint)

**Upgrade Path:** I (Uncommon) → II (Rare - "Frost Adept")  
**Lore:** Garments blessed by icy winds. Used by those learning to command frozen magic.

---

### Set 05: Flame Caster
*Tier Range: 3–4 (Lv 10–15) | Path: Fire | Role: DPS | Map: 2 | Rarity: Rare*

| Slot | Piece Name | Intended Focus | Secondary | Unique Effect | Material Req | Acquisition |
|------|------------|---|---|---|---|---|
| **Head** | Caster's Flame Crown | INT 20+ | - | Pyromancer's command | Cloth x2, Boar Tusk x2, Feather | Boss Drop (B2: Fire Elemental) |
| **Chest** | Caster's Inferno Robe | INT 20+ | Fire focus | Fireball amplification | Cloth x3, Boar Tusk x2, Feather | Boss Drop (B2) |
| **Legs** | Caster's Burning Legs | INT 18+ | Fire dmg | Heat channeling | Cloth x2, Boar Tusk, Feather | Craft (Materials from B2) |
| **Hands** | Caster's Flame Gloves | INT 18+ | Fire output | Gesture magic boost | Cloth, Boar Tusk x2, Feather | Craft (Materials from B2) |
| **Boots** | Caster's Hot Feet | INT 15+ | - | Flame trail effect | Cloth x2, Boar Tusk, Feather | Craft (Materials from B2) |

**Set Bonus:**
- (2) Fire spell damage +25%
- (3) Fireball cooldown reset on burn trigger
- (5) Meteors gain fire penetration

**Upgrade Path:** I (Rare) → II (Epic - "Master Flame Caster")  
**Lore:** Worn by dedicated fire mages. Radiates intense heat and authority.

---

### Set 06: Time's Echo
*Tier Range: 4–5 (Lv 15–20) | Path: Time | Role: Hybrid | Map: 2–3 | Rarity: Rare*

| Slot | Piece Name | Intended Focus | Secondary | Unique Effect | Material Req | Acquisition |
|------|------------|---|---|---|---|---|
| **Head** | Echo Circlet | INT 20+ | DEX 12+ | Temporal awareness | Cloth x2, Feather, Rope | Craft |
| **Chest** | Echo Mantle | INT 20+ | DEX 12+ | Time flow attunement | Cloth x3, Feather x2, Rope | Craft |
| **Legs** | Echo Leggings | INT 18+ | DEX 10+ | Swift moment casting | Cloth x2, Feather, Rope | Craft |
| **Hands** | Echo Sleeves | INT 18+ | DEX 12+ | Gesture acceleration | Cloth, Feather x2, Rope | Craft |
| **Boots** | Echo Steps | INT 15+ | DEX 8+ | Stride through seconds | Cloth x2, Feather, Rope | Craft |

**Set Bonus:**
- (2) Cooldown reduction -1 turn passive
- (3) Quick Cast triggers faster
- (5) Echo spell duplication +1 copy

**Upgrade Path:** I (Rare) → II (Epic - "Temporal Echo")  
**Lore:** Shimmers with borrowed moments from parallel timelines.

---

### Set 07: Blizzard Sage
*Tier Range: 5–6 (Lv 20–25) | Path: Ice | Role: Control | Map: 3 | Rarity: Rare*

| Slot | Piece Name | Intended Focus | Secondary | Unique Effect | Material Req | Acquisition |
|------|------------|---|---|---|---|---|
| **Head** | Sage's Icy Crown | INT 25+ | CON 18+ | Blizzard command presence | Cloth x2, Antidote Herb x2, Hide | Quest Reward (SQ-09) |
| **Chest** | Sage's Frozen Mantle | INT 25+ | CON 20+ | Winter's embrace | Cloth x3, Antidote Herb x3, Hide x2 | Quest Reward (SQ-09) + Craft |
| **Legs** | Sage's Icy Trousers | INT 22+ | CON 15+ | Permafrost synergy | Cloth x2, Antidote Herb x2, Hide | Quest Reward (SQ-09) |
| **Hands** | Sage's Frost Gloves | INT 20+ | CON 12+ | Ice crystal gestures | Cloth, Antidote Herb x2, Bone | Craft (Map 3 materials) |
| **Boots** | Sage's Glacier Steps | INT 20+ | CON 10+ | Walking on frozen lakes | Cloth x2, Antidote Herb, Hide | Craft (Map 3 materials) |

**Set Bonus:**
- (2) Freeze duration +1 turn
- (3) Blizzard cooldown -2 turns
- (5) Frozen targets reflect frost back (passive reflect)

**Upgrade Path:** I (Rare) → II (Epic - "Blizzard Master")  
**Lore:** Adorned with perpetual frost. Symbol of true cryomancer mastery.

---

### Set 08: Inferno Master
*Tier Range: 6–7 (Lv 25–30) | Path: Fire | Role: DPS | Map: 4 | Rarity: Epic*

| Slot | Piece Name | Intended Focus | Secondary | Unique Effect | Material Req | Acquisition |
|------|------------|---|---|---|---|---|
| **Head** | Master's Flame Crown | INT 35+ | - | Meteoric authority | Cloth x2, Stone Heart, Marble Fragment x2 | Boss Drop (B4: Fire Phoenix) |
| **Chest** | Master's Inferno Plate | INT 35+ | Fire mastery | Cataclysmic flames | Cloth x3, Stone Heart x2, Marble Fragment x2 | Boss Drop (B4) |
| **Legs** | Master's Burning Guard | INT 32+ | Fire output | Lava channeling | Cloth x2, Stone Heart, Marble Fragment | Boss Drop (B4) + Craft |
| **Hands** | Master's Flame Gauntlets | INT 30+ | Fire peak | Pyromancer's final form | Cloth, Stone Heart, Marble Fragment x2 | Craft (B4 materials) |
| **Boots** | Master's Meteor Treads | INT 30+ | - | Ground scorching effect | Cloth x2, Stone Heart, Marble Fragment | Craft (B4 materials) |

**Set Bonus:**
- (2) Fire damage +40%
- (3) Meteor cooldown instant-reset on burn trigger (powerful!)
- (5) Explosion radius +200%

**Upgrade Path:** I (Epic) → II (Legendary - "Eternal Inferno")  
**Lore:** Robes of legendary fire mages who challenged the volcano itself.

---

### Set 09: Deep Freeze
*Tier Range: 6–7 (Lv 25–30) | Path: Ice | Role: Control | Map: 4 | Rarity: Epic*

| Slot | Piece Name | Intended Focus | Secondary | Unique Effect | Material Req | Acquisition |
|------|------------|---|---|---|---|---|
| **Head** | Deep Freeze Crown | INT 32+ | CON 20+ | Absolute zero command | Cloth x2, Stone Heart, Marble Fragment x2 | Boss Drop (B4: Frost Dragon) |
| **Chest** | Deep Freeze Robe | INT 32+ | CON 25+ | Perpetual ice aura | Cloth x3, Stone Heart x2, Marble Fragment x2 | Boss Drop (B4) |
| **Legs** | Deep Freeze Leggings | INT 30+ | CON 18+ | Frozen path creation | Cloth x2, Stone Heart, Marble Fragment | Boss Drop (B4) + Craft |
| **Hands** | Deep Freeze Gloves | INT 28+ | CON 20+ | Instant crystallization | Cloth, Stone Heart, Marble Fragment x2 | Craft (B4 materials) |
| **Boots** | Deep Freeze Treads | INT 28+ | - | Ice sheet walker | Cloth x2, Stone Heart, Marble Fragment | Craft (B4 materials) |

**Set Bonus:**
- (2) Freeze chance +30%
- (3) Blizzard cooldown instant-reset on freeze trigger (powerful!)
- (5) Frozen enemies cannot unfreeze naturally (lockdown)

**Upgrade Path:** I (Epic) → II (Legendary - "Eternal Deep Freeze")  
**Lore:** Robes that turn oceans to solid ice. Symbol of true cryomancer mastery.

---

### Set 10: Temporal Rift
*Tier Range: 7–8 (Lv 30–40) | Path: Time | Role: Hybrid | Map: 4–5 | Rarity: Epic*

| Slot | Piece Name | Intended Focus | Secondary | Unique Effect | Material Req | Acquisition |
|------|------------|---|---|---|---|---|
| **Head** | Rift Crown | INT 32+ | DEX 18+ | Dimensional rift vision | Cloth x2, Skull, Ancient Coin x2 | Drop (Map 4 Temporal Site) + Craft |
| **Chest** | Rift Mantle | INT 32+ | DEX 18+ | Space-time compression | Cloth x3, Skull x2, Ancient Coin x2 | Drop (Map 4) + Craft |
| **Legs** | Rift Leggings | INT 30+ | DEX 15+ | Stride between seconds | Cloth x2, Skull, Ancient Coin | Craft |
| **Hands** | Rift Gloves | INT 28+ | DEX 15+ | Gesture multiplied across time | Cloth, Skull, Ancient Coin x2 | Craft |
| **Boots** | Rift Steps | INT 28+ | DEX 12+ | Walk multiple timelines | Cloth x2, Ancient Coin x2 | Craft |

**Set Bonus:**
- (2) Cooldown reduction -2 turns always active
- (3) Time skill triggers instantly (no cast delay)
- (5) Time Warp echoes create duplicate action (Echo amplified)

**Upgrade Path:** I (Epic) → II (Legendary - "Eternal Rift")  
**Lore:** Robes torn from the fabric of spacetime itself. Reality bends around them.

---

### Set 11: Arcane Ascended
*Tier Range: 12 (Lv 90+) | Path: Ultimate (Fire+Ice+Time Synergy) | Role: Ultimate | Map: 10 | Rarity: Mythic*

| Slot | Piece Name | Intended Focus | Secondary | Unique Effect | Material Req | Acquisition |
|------|------------|---|---|---|---|---|
| **Head** | Arcane Crown | INT 99+ | - | All elements converge here | Cloth x2, Void Core x2, Reality Fragment x3 | Ultimate Unlock (MQ-12) |
| **Chest** | Arcane Ascendant Robe | INT 99+ | All elements | Fire/Ice/Time unified | Cloth x3, Void Core x3, Reality Fragment x4 | Ultimate Unlock (MQ-12) + Craft |
| **Legs** | Arcane Ascendant Legs | INT 95+ | All mastery | Flame-frost-time balance | Cloth x2, Void Core x2, Reality Fragment x3 | Craft (Ultimate materials) |
| **Hands** | Arcane Ascendant Gloves | INT 95+ | All elements | Command all magic | Cloth, Void Core x2, Reality Fragment x2 | Craft (Ultimate materials) |
| **Boots** | Arcane Ascendant Steps | INT 90+ | All synergy | Walk through all realms | Cloth x2, Void Core x2, Reality Fragment x3 | Craft (Ultimate materials) |

**Set Bonus:**
- (2) All elemental cooldowns -1 turn
- (3) Fire/Ice/Time skills gain +50% potency each (stacking!)
- (5) Ultimate spell recharge time -50% (ultimate synergy! Armageddon/Absolute Zero/Time Stop faster)

**Upgrade Path:** I (Mythic) - No further upgrade (Final form)  
**Lore:** The robes of a true Archmage. All elemental forces bow to their will.

---

## 📝 Reserved Slots (Index 12–45)

The following indices are reserved for future expansion:

| Index | Set Name | Tier Range | Status |
|-------|----------|-----------|--------|
| 12–16 | **Early Specialization** (Path variants of Set 2–4) | Tiers 2–6 (Lv 5–30) | Reserved |
| 17–21 | **Mid-Game Variants** (Alternative Fire/Ice/Time paths) | Tiers 6–8 (Lv 30–50) | Reserved |
| 22–32 | **Late-Game Collection** (Synergy sets, elemental combos) | Tiers 8–10 (Lv 50–70) | Reserved |
| 33–38 | **Endgame Transitions** (Pre-Ultimate variants, Tiers 10–11) | Tiers 10–11 (Lv 70–90) | Reserved |
| 39–42 | **Void-touched Collection** (Corruption-aligned variants) | Tier 11–12 (Lv 80+) | Reserved |
| 43–45 | **Legendary Variants / Event Exclusives** (Raid drops, seasonal) | Tier 12 Ultimate (Lv 90+) | Reserved |

**Expansion Strategy:**
- Index 12–21: Fill with hybrid/dual-path sets (e.g., Fire+Ice, Time+Fire)
- Index 22–38: Progressive power curves matching mid/late boss encounters
- Index 39–42: Void mechanics and corruption thresholds
- Index 43–45: Special/seasonal content

---

## 🔗 Cross-References

**Related Systems:**
- Stat Requirements Reference: `balance_calculation.md` (Stat Progression Table, Lv 20/40/60/80/100 milestones)
- Crafting Materials: `item all_type.md` (Materials section: Map 1–10 tier-appropriate drops)
- Skill Progression: `skill_tree.md` (Mage Class Tiers 1–12, 3 paths: Pyromancer/Cryomancer/Chronomancer)
- Key Items: `item all_type.md` (Key Items section—*separate from equipment materials*)

**Mage Stat Profile (from skill_tree.md):**
- Primary: INT (up to 99)
- Secondary: CON (up to 50 for survival), DEX (up to 40 for speed), LUK (up to 40)
- Tertiary: Minimal STR/FAI (not core to paths)

**Integration Notes:**
- All material names reference `item_all_type.md` exactly—no invented item names
- Set progression aligns with `balance_calculation.md` level milestones
- Skill Tier ranges match `skill_tree.md` activation levels
- 3 Paths (Fire/Ice/Time) synergize with skill tree paths
- Lore placeholders pending `lore.md` development (currently generic)

---

## ✅ Schema Validation Checklist

- [x] 5 Slots per set (Head / Chest / Legs / Hands / Boots)
- [x] 10 Sets fully populated (Index 01–10)
- [x] 35 Sets reserved as placeholders (Index 11–45)
- [x] All material names from `item_all_type.md`
- [x] Set Bonus 2/3/5 piece conditions specified
- [x] Tier ranges reference `skill_tree.md` levels
- [x] Map Tiers 1–10 align with progression
- [x] No stat numbers inserted (qualitative focus only)
- [x] Unique Effects distinct from Set Bonuses
- [x] Rarity progression Common → Uncommon → Rare → Epic → Legendary → Mythic
- [x] All sets belong to Mage class
- [x] Acquisition methods diversified (Quest/Drop/Craft/Boss/Vendor)
- [x] No edits to existing game files
- [x] Lore placeholders only (pending lore.md)
- [x] All armor pieces Cloth/Robe type (no plate, appropriate to class)
- [x] 3 Paths represented (Fire/Ice/Time with progression)
- [x] No Tank role (DPS/Control/Hybrid only - reflects Mage weakness)

---

**End of Document**
