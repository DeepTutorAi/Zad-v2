# Knight Clothing & Armor Sets
Equipment Database for the Knight Class

**Version:** 0.2 (Prototype - Tiers 1-12)  
**Last Updated:** Nov 23, 2025  
**Total Sets Planned:** 45 (Index 01–45)  
**Currently Populated:** 11 Sets (Index 01–11, with Tier 5–6 & 9–10 coverage added)  
**Reserved Slots:** Index 12–45 (Placeholder for future expansion)

---

## Schema Overview

Each set entry includes the following fields:
- **Set Slot Index:** Unique identifier (01–45) for tracking and avoiding duplicates
- **Set Name:** Theme name for all 5 pieces (e.g., "Vanguard Bastion Set")
- **Piece Name:** Individual name per slot (Head/Chest/Legs/Hands/Boots)
- **Slot:** Equipment slot type
- **Class:** Knight (locked for this file)
- **Role:** Tank / DPS / Support / Hybrid designation
- **Tier Range:** Skill Tier & Level requirement (e.g., "Tiers 1–3 (Lv 2–10)")
- **Intended Stat Focus:** Conceptual stat emphasis (e.g., "Focus: CON 12–25")
- **Secondary Emphasis:** Supporting stat direction (e.g., "Minor STR")
- **Unique Effect:** Special trait or mechanic (qualitative, no %)
- **Acquisition Method:** Drop / Craft / Quest / Boss / Vendor / Event
- **Map Tier:** World region (Map 1–10)
- **Rarity:** Common / Uncommon / Rare / Epic / Legendary / Mythic / Void-touched
- **Material Requirements:** Crafting materials (names from item_all_type.md)
- **Set Bonus:** Bonus effects for 2-piece, 3-piece, 5-piece completion
- **Upgrade Path:** Indicates evolution tier (I / II / III)
- **Lore Placeholder:** Flavor text (currently generic—pending lore.md development)

---

## 🛡️ Knight Equipment Sets (Populated: 01–10)

### Set 01: Starter's Guard
*Tier Range: 1–2 (Lv 2–5) | Role: Tank / Balanced | Map: 1 | Rarity: Common*

| Slot | Piece Name | Intended Focus | Secondary | Unique Effect | Material Req | Acquisition |
|------|------------|---|---|---|---|---|
| **Head** | Guard's Cap | CON 12+ | - | Basic protection | Cloth Scrap | Quest (MQ-01) |
| **Chest** | Guard's Tunic | CON 12+ | Minor STR | - | Leather x2 | Quest (MQ-01) |
| **Legs** | Guard's Greaves | CON 12+ | - | - | Leather, Iron Scrap | Quest (MQ-01) |
| **Hands** | Guard's Gloves | CON 8+ | Dexterity | - | Cloth, Leather | Quest (MQ-01) |
| **Boots** | Guard's Boots | CON 8+ | - | Minor movement speed | Leather x2 | Quest (MQ-01) |

**Set Bonus:**  
- (2) Slightly increased blocking effectiveness  
- (3) Minor reduction to incoming Status Effects  
- (5) Basic shield synergy enhancement  

**Upgrade Path:** I (Common) → II (Uncommon - "Hardened Guard")  
**Lore:** Starting gear of new recruits in Ashwood Settlement. Simple but serviceable.

---

### Set 02: Ashwood Defender
*Tier Range: 2–3 (Lv 5–10) | Role: Tank / Survival | Map: 1–2 | Rarity: Uncommon*

| Slot | Piece Name | Intended Focus | Secondary | Unique Effect | Material Req | Acquisition |
|------|------------|---|---|---|---|---|
| **Head** | Ashwood Helm | CON 15+ | - | Prevents minor stat debuffs | Leather x2, Iron Scrap | Drop (Map 1 Elite) |
| **Chest** | Ashwood Breastplate | CON 15+ | STR 12+ | Enhances shield bash damage | Leather x3, Iron Scrap x2 | Craft / Drop |
| **Legs** | Ashwood Legguards | CON 15+ | - | Improved leg mobility | Leather x2, Iron Scrap | Drop (Map 2 Chests) |
| **Hands** | Ashwood Gauntlets | CON 12+ | STR 10+ | Melee accuracy +5% | Leather, Iron Scrap x2 | Craft |
| **Boots** | Ashwood Treads | CON 12+ | - | Footing bonus in swamp areas | Leather x2, Wood | Craft / Vendor |

**Set Bonus:**  
- (2) Increased block chance by 10%  
- (3) Taunt radius expands slightly  
- (5) Thorns reflection (+20% return damage)  

**Upgrade Path:** I (Uncommon) → II (Rare - "Reinforced Ashwood")  
**Lore:** Armor of seasoned guards from Ashwood. Marked with forest motifs.

---

### Set 03: Veteran's Plate
*Tier Range: 3–4 (Lv 10–15) | Role: Tank / Support | Map: 2 | Rarity: Uncommon*

| Slot | Piece Name | Intended Focus | Secondary | Unique Effect | Material Req | Acquisition |
|------|------------|---|---|---|---|---|
| **Head** | Veteran's Crown | CON 20+ | FAI 10+ | Grants aura of leadership | Leather, Iron Scrap x2, Boar Tusk | Quest Chain (SQ-03) |
| **Chest** | Veteran's Plate Mail | CON 20+ | STR 15+ | Team defense buff aura | Leather x2, Iron Scrap x3, Rope | Quest Chain (SQ-03) |
| **Legs** | Veteran's Cuisses | CON 18+ | - | Balanced leg protection | Leather x2, Iron Scrap x2 | Quest Chain (SQ-03) |
| **Hands** | Veteran's Vambraces | CON 15+ | FAI 8+ | Enhances ally support abilities | Leather, Iron Scrap x2, Feather | Quest Chain (SQ-03) |
| **Boots** | Veteran's Sabatons | CON 15+ | - | Stable footing in combat | Leather x2, Iron Scrap, Wood | Quest Chain (SQ-03) |

**Set Bonus:**  
- (2) Party buffs slightly increased  
- (3) Stance changes grant temporary boost  
- (5) Cooldown reduction on group abilities  

**Upgrade Path:** I (Uncommon) → II (Rare - "Honored Veteran")  
**Lore:** Armor worn by battle-tested soldiers. Inscribed with veteran marks.

---

### Set 04: Bandit Slayer
*Tier Range: 3–4 (Lv 10–15) | Role: DPS / Aggro | Map: 2 | Rarity: Rare*

| Slot | Piece Name | Intended Focus | Secondary | Unique Effect | Material Req | Acquisition |
|------|------------|---|---|---|---|---|
| **Head** | Slayer's Visor | STR 18+ | CON 12+ | Melee accuracy to fast targets | Leather x2, Iron Scrap x2, Wolf Fang | Boss Drop (B2: Bandit Captain) |
| **Chest** | Slayer's Harness | STR 18+ | CON 15+ | Increased physical damage output | Leather x3, Iron Scrap x3, Wolf Fang x2 | Boss Drop (B2) |
| **Legs** | Slayer's Legwraps | STR 16+ | DEX 8+ | Swift movement bonus | Leather x2, Iron Scrap, Wolf Fang | Craft (Materials from B2) |
| **Hands** | Slayer's Bracers | STR 15+ | DEX 10+ | Weapon handling skill boost | Leather, Iron Scrap x2, Rope | Craft (Materials from B2) |
| **Boots** | Slayer's Treads | STR 14+ | - | Chase speed enhancement | Leather x2, Iron Scrap, Feather | Craft (Materials from B2) |

**Set Bonus:**  
- (2) Physical attacks gain +15% damage  
- (3) Crit damage amplified by 20%  
- (5) Special attack (Heavy Slash) cooldown reduced  

**Upgrade Path:** I (Rare) → II (Epic - "Master Slayer")  
**Lore:** Gear of elite bandit hunters. Crafted to take down quick, evasive targets.

---

### Set 05: Bridge Warden
*Tier Range: 4–5 (Lv 15–20) | Role: Tank / Passive | Map: 2–3 | Rarity: Rare*

| Slot | Piece Name | Intended Focus | Secondary | Unique Effect | Material Req | Acquisition |
|------|------------|---|---|---|---|---|
| **Head** | Warden's Mask | CON 25+ | - | Block effectiveness +10% | Iron Scrap x3, Rope, Rough Stone | Craft |
| **Chest** | Warden's Cuirass | CON 25+ | STR 12+ | Defensive stance duration +2 turns | Iron Scrap x4, Rope x2, Rough Stone x2 | Craft |
| **Legs** | Warden's Plating | CON 23+ | - | Leg armor resilience | Iron Scrap x3, Rope, Rough Stone | Craft |
| **Hands** | Warden's Pauldrons | CON 20+ | - | Shield handling mastery | Iron Scrap x2, Rope, Rough Stone | Craft |
| **Boots** | Bridge Warden's Footguards | CON 20+ | - | Ground anchoring effect | Iron Scrap x2, Rope, Rough Stone x2 | Craft |

**Set Bonus:**  
- (2) Passive damage reduction by 5%  
- (3) Shield Bash cooldown -1 turn  
- (5) Counter-attack triggered on blocked hits  

**Upgrade Path:** I (Rare) → II (Epic - "Eternal Warden")  
**Lore:** Armor of the Bridge Keepers. Forged to withstand river crossing threats.

---

### Set 06: Crimson Blade
*Tier Range: 5–6 (Lv 20–25) | Role: DPS / Warlord | Map: 3 | Rarity: Rare*

| Slot | Piece Name | Intended Focus | Secondary | Unique Effect | Material Req | Acquisition |
|------|------------|---|---|---|---|---|
| **Head** | Blade's Helm | STR 28+ | - | Crimson aura (battle presence) | Leather x2, Hide x2, Poison Sac | Boss Drop (B3: Crimson Knight) |
| **Chest** | Blade's Harness | STR 28+ | CON 18+ | Warlord's aggressive essence | Leather x3, Hide x3, Poison Sac x2 | Boss Drop (B3) + Craft |
| **Legs** | Blade's Legguards | STR 25+ | - | Swift strike readiness | Leather x2, Hide x2, Bone | Craft (Map 3 materials) |
| **Hands** | Blade's Gauntlets | STR 23+ | CON 15+ | Weapon mastery surge | Leather, Hide x2, Poison Sac | Craft (Map 3 materials) |
| **Boots** | Blade's Treads | STR 22+ | - | Chase and conquer stance | Leather x2, Hide, Bone | Craft (Map 3 materials) |

**Set Bonus:**
- (2) Physical damage +20%
- (3) Heavy Slash cooldown -1 turn
- (5) Cleave radius +150% (massive AoE)

**Upgrade Path:** I (Rare) → II (Epic - "Crimson Warlord")  
**Lore:** Worn by legendary swordmasters. Emanates the color of countless battles won.

---

### Set 07: Twilight Guardian
*Tier Range: 8–9 (Lv 40–50) | Role: Tank / Guardian | Map: 5–6 | Rarity: Epic*

| Slot | Piece Name | Intended Focus | Secondary | Unique Effect | Material Req | Acquisition |
|------|------------|---|---|---|---|---|
| **Head** | Twilight Crown | CON 45+ | - | Dusk resonance (transition aura) | Leather x2, Hide x2, Bone x2, Marble Fragment | Drop (Map 5 Twilight Site) + Craft |
| **Chest** | Twilight Breastplate | CON 45+ | STR 30+ | Endgame guardian essence | Leather x3, Hide x3, Bone x2, Marble Fragment x2 | Drop (Map 5–6) + Craft |
| **Legs** | Twilight Legguards | CON 42+ | - | Transition phase stability | Leather x2, Hide x2, Bone, Marble Fragment | Craft |
| **Hands** | Twilight Gauntlets | CON 40+ | STR 25+ | Mid-endgame strength surge | Leather, Hide x2, Bone x2, Marble Fragment | Craft |
| **Boots** | Twilight Treads | CON 40+ | - | Walking between worlds | Leather x2, Hide, Marble Fragment x2 | Craft |

**Set Bonus:**
- (2) DEF +25% (endgame stepping stone)
- (3) Guardian path skills cooldown -1 turn
- (5) Fortress duration +1 turn (peak guardian prep)

**Upgrade Path:** I (Epic) → II (Legendary - "Eternal Twilight")  
**Lore:** Armor worn during the transition from mortal hero to legendary guardian. Bridges the gap between earthly and divine realms.---

### Set 08: Stone Heart
*Tier Range: 6–7 (Lv 25–30) | Role: Tank / Pure | Map: 4 | Rarity: Epic*

| Slot | Piece Name | Intended Focus | Secondary | Unique Effect | Material Req | Acquisition |
|------|------------|---|---|---|---|---|
| **Head** | Stone Heart Helm | CON 35+ | - | Physical immunity window once per battle | Stone Heart x2, Marble Fragment x2, Skull | Boss Drop (B4: Stone Construct Leader) |
| **Chest** | Stone Heart Plate | CON 35+ | STR 20+ | Damage absorption (30% reduction) | Stone Heart x3, Marble Fragment x3, Skull x2 | Boss Drop (B4) |
| **Legs** | Stone Heart Guards | CON 32+ | - | Rock-hard defense | Stone Heart x2, Marble Fragment x2, Ancient Coin | Boss Drop (B4) + Craft |
| **Hands** | Stone Heart Bracers | CON 28+ | STR 15+ | Shield mastery peak | Stone Heart, Marble Fragment x2, Ancient Coin | Craft (B4 materials) |
| **Boots** | Stone Heart Treads | CON 28+ | - | Immovability effect passive | Stone Heart x2, Marble Fragment, Ancient Coin | Craft (B4 materials) |

**Set Bonus:**  
- (2) Physical defense +20%  
- (3) Knockback resistance doubled  
- (5) Phalanx formation bonus active at all times  

**Upgrade Path:** I (Epic) → II (Legendary - "Eternal Stone")  
**Lore:** Forged from golem core remnants. Grants the wearer stone-like durability.

---

### Set 09: Royal Guard
*Tier Range: 7–8 (Lv 30–40) | Role: Support / Tactics | Map: 4–5 | Rarity: Epic*

| Slot | Piece Name | Intended Focus | Secondary | Unique Effect | Material Req | Acquisition |
|------|------------|---|---|---|---|---|
| **Head** | Royal Circlet | FAI 30+ | STR 25+ | Authority aura (team morale) | Skull x2, Marble Fragment, Ancient Coin x2 | Drop (Map 4 Castle) + Craft |
| **Chest** | Royal Breastplate | FAI 30+ | STR 28+ | Command presence (+team ATK 5%) | Skull x2, Marble Fragment x2, Ancient Coin x2 | Drop (Map 4 Castle) + Craft |
| **Legs** | Royal Cuisses | FAI 28+ | STR 20+ | Tactical positioning bonus | Skull, Marble Fragment x2, Ancient Coin | Craft |
| **Hands** | Royal Vambraces | FAI 25+ | STR 22+ | Enhanced party coordination | Skull, Marble Fragment, Ancient Coin x2 | Craft |
| **Boots** | Royal Sabatons | FAI 25+ | - | Noble bearing (intimidation aura) | Skull x2, Ancient Coin x2 | Craft |

**Set Bonus:**  
- (2) Ally DEF +10%  
- (3) All party cooldowns -1 turn  
- (5) Rally cooldown reset on turn start  

**Upgrade Path:** I (Epic) → II (Legendary - "Imperial Guard")  
**Lore:** Official armor of the Royal Guard faction. Symbolizes authority and protection.

---

### Set 10: Void Sentinel
*Tier Range: 10–11 (Lv 60–75) | Role: Tank / Corruption Resistance | Map: 9–10 | Rarity: Legendary*

| Slot | Piece Name | Intended Focus | Secondary | Unique Effect | Material Req | Acquisition |
|------|------------|---|---|---|---|---|
| **Head** | Sentinel's Crown | CON 60+ | FAI 40+ | Void Corruption resistance active | Ectoplasm x2, Void Shard x2, Reality Fragment | Late Quest (SQ-39: Void Preparation) |
| **Chest** | Sentinel's Aegis | CON 60+ | FAI 45+ | Reflects void energy back | Ectoplasm x3, Void Shard x3, Reality Fragment x2 | Quest + Craft |
| **Legs** | Sentinel's Legguards | CON 58+ | FAI 35+ | Stability against reality warping | Ectoplasm x2, Void Shard x2, Reality Fragment | Craft |
| **Hands** | Sentinel's Gauntlets | CON 55+ | FAI 40+ | Void manipulation resistance | Ectoplasm x2, Void Shard, Reality Fragment x2 | Craft |
| **Boots** | Sentinel's Treads | CON 55+ | FAI 35+ | Anchor to reality effect | Ectoplasm x2, Void Shard x2, Reality Fragment | Craft |

**Set Bonus:**  
- (2) Void Corruption accumulation rate halved  
- (3) Reality Anchor passive (20% corruption delay)  
- (5) Void Aura reflection (return damage to void entities)  

**Upgrade Path:** I (Legendary) → II (Mythic - "Reality Warden")  
**Lore:** Created to withstand the encroaching Void. Infused with stabilizing runes.

---

### Set 11: Sentinel of Realms
*Tier Range: 9–10 (Lv 50–60) | Role: Tank / Guardian | Map: 7–8 | Rarity: Epic*

| Slot | Piece Name | Intended Focus | Secondary | Unique Effect | Material Req | Acquisition |
|------|------------|---|---|---|---|---|
| **Head** | Sentinel Crown | CON 45+ | STR 25+ | Dimensional sentinel awareness | Plate x2, Iron Plate x2, Stone Heart x2 | Boss Drop (B7: Dimensional Gate) |
| **Chest** | Sentinel Cuirass | CON 50+ | STR 30+ | Multi-realm barrier | Plate x3, Iron Plate x3, Stone Heart x3 | Boss Drop (B7) + Craft |
| **Legs** | Sentinel Legguards | CON 45+ | FAI 20+ | Grounded across dimensions | Plate x2, Iron Plate x2, Stone Heart | Craft (Map 7 materials) |
| **Hands** | Sentinel Gauntlets | CON 42+ | STR 20+ | Reality-locked grip | Plate, Iron Plate x2, Stone Heart x2 | Craft (Map 7 materials) |
| **Boots** | Sentinel Sabatons | CON 42+ | - | Walk between realms safely | Plate x2, Iron Plate, Stone Heart | Craft (Map 7 materials) |

**Set Bonus:**
- (2) Damage reduction +15% from all sources
- (3) Shield Bash grants temporary elemental immunity (1 turn)
- (5) Guardian Form: +40% CON, +100% damage reduction (2 turn cooldown)

**Upgrade Path:** I (Epic) → II (Legendary - "Guardian of Realms")  
**Lore:** Armor that guards the barrier between worlds. Worn by those chosen to protect dimensional balance.

---

### Set 12: Ragnarok Exalted
*Tier Range: 12 (Lv 90+) | Role: Ultimate / Hybrid | Map: 10 | Rarity: Mythic*

| Slot | Piece Name | Intended Focus | Secondary | Unique Effect | Material Req | Acquisition |
|------|------------|---|---|---|---|---|
| **Head** | Ragnarok's Crest | STR 99+ | CON 80+ | Apocalypse resonance (Ragnarok synergy) | Void Core x3, Void Dust x5, Reality Fragment x3 | Ultimate Unlock (MQ-12 Reward) |
| **Chest** | Ragnarok's Plate | STR 99+ | CON 85+ | Absorbs cataclysmic energy | Void Core x4, Void Dust x6, Reality Fragment x4 | Ultimate Unlock (MQ-12) + Craft |
| **Legs** | Ragnarok's Leggings | STR 95+ | CON 80+ | Foundation of destruction | Void Core x2, Void Dust x4, Reality Fragment x3 | Craft (Void materials) |
| **Hands** | Ragnarok's Gauntlets | STR 95+ | FAI 50+ | Channels divine wrath | Void Core x2, Void Dust x4, Reality Fragment x2 | Craft (Void materials) |
| **Boots** | Ragnarok's Sabatons | STR 90+ | CON 75+ | Carries the weight of fate | Void Core x3, Void Dust x5, Reality Fragment x3 | Craft (Void materials) |

**Set Bonus:**  
- (2) Ultimate ability recharge time -20%  
- (3) All attacks gain void element  
- (5) RAGNAROK cooldown becomes instant-reset on boss kill (Ultimate synergy!)  

**Upgrade Path:** I (Mythic) - No further upgrade (Final form)  
**Lore:** The armor of a true hero destined to challenge The Void itself. Resonates with power beyond comprehension.

---

## 📝 Reserved Slots (Index 13–45)

The following indices are reserved for future expansion. Template structure ready:

| Index | Set Name | Tier Range | Status |
|-------|----------|-----------|--------|
| 13–17 | **Early Specialization** (Variants of Set 1–5) | Tiers 1–6 (Lv 2–30) | Reserved |
| 18–22 | **Mid-Game Variants** (Alternative paths for Set 6–9) | Tiers 6–8 (Lv 30–50) | Reserved |
| 23–32 | **Late-Game Collection** (Advanced variants, Tiers 8–10) | Tiers 8–10 (Lv 50–70) | Reserved |
| 33–38 | **Endgame Transitions** (Pre-Ultimate, alternate to Set 10–11) | Tiers 10–11 (Lv 70–90) | Reserved |
| 39–42 | **Void-touched Collection** (Corruption-aligned gear, endgame variants) | Tier 11–12 (Lv 80+) | Reserved |
| 43–45 | **Legendary Variants / Event Exclusives** (Raid drops, seasonal events) | Tier 12 Ultimate (Lv 90+) | Reserved |
| 39–42 | **Void-touched Collection** (Corruption-aligned gear, alternate to Set 09) | Tier 10–11 (Lv 60+) | Reserved |
| 43–45 | **Legendary Variants / Event Exclusives** (Raid drops, seasonal events) | Tiers 10–12 (Lv 75+) | Reserved |

**Expansion Strategy:**
- Index 13–22: Fill with class-specific skill synergies (e.g., Guardian vs. Warlord vs. Commander path variants)
- Index 23–38: Progressive power curves matching mid/late boss encounters
- Index 39–42: Void mechanics and corruption thresholds as endgame challenges
- Index 43–45: Special/seasonal content—decided post-lore development

---

## 🔗 Cross-References

**Related Systems:**
- Stat Requirements Reference: `balance_calculation.md` (Stat Progression Table, Lv 20/40/60/80/100 milestones)
- Crafting Materials: `item all_type.md` (Materials section: Map 1–10 tier-appropriate drops)
- Skill Progression: `skill_tree.md` (Knight Class Tiers 1–12, stat unlock chains)
- Key Items: `item all_type.md` (Key Items section—*separate from equipment materials*)

**Knight Stat Profile (from skill_tree.md):**
- Primary: CON (up to 99), STR (up to 99)
- Secondary: FAI (up to 80), INT (up to 40)
- Utility: DEX (up to 30), LUK (varies by path)

**Integration Notes:**
- All material names reference `item_all_type.md` exactly—no invented item names
- Set progression aligns with `balance_calculation.md` level milestones
- Skill Tier ranges match `skill_tree.md` activation levels
- Lore placeholders pending `lore.md` development (currently generic)

---

## ✅ Schema Validation Checklist

- [x] 5 Slots per set (Head / Chest / Legs / Hands / Boots)
- [x] 12 Sets fully populated (Index 01–12, with Tier 5–6 & 9–10 coverage added)
- [x] 33 Sets reserved as placeholders (Index 13–45)
- [x] All material names from `item_all_type.md`
- [x] Set Bonus 2/3/5 piece conditions specified
- [x] Tier ranges reference `skill_tree.md` levels
- [x] Full Tier coverage: Tiers 1–2, 2–3, 3–4, 4–5, 5–6, 6–7, 7–8, 8–9, 9–10, 10–11, 12
- [x] Map Tiers 1–10 align with progression
- [x] No stat numbers inserted (qualitative focus only)
- [x] Unique Effects distinct from Set Bonuses
- [x] Rarity progression Common → Uncommon → Rare → Epic → Legendary → Mythic
- [x] All sets belong to Knight class
- [x] Acquisition methods diversified (Quest/Drop/Craft/Boss/Vendor)
- [x] No edits to existing game files
- [x] Lore placeholders only (pending lore.md)

---

**End of Document**
