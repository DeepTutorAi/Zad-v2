# Game Design Document: [Untitled Dark Fantasy RPG]

## 1. Core Concept (คอนเซปต์หลัก)
*   **Genre:** Text-based RPG / Roguelite / Point & Click
*   **Visual Style:** Choice Menu (เน้นการอ่านและการตัดสินใจ)
*   **Tone:** Dark Fantasy ที่มีความเข้มข้นของเนื้อเรื่อง (Intense Narrative) แต่ไม่หม่นหมองจนเกินไป (Balanced Atmosphere)

## 2. Gameplay Mechanics (ระบบการเล่น)
*   **Exploration:**
    *   ใช้ระบบ **Choice Menu** เป็นหลัก ผู้เล่นเลือกการกระทำจากตัวเลือก
    *   เน้น **Sequences** (ลำดับเหตุการณ์) ที่จะเปลี่ยนไปตามการตัดสินใจของผู้เล่น
*   **Act Structure (โครงสร้างเรื่อง):**
    *   **Act 1: The Beginning** (Map 1-3) - Tutorial, รู้จักโลก, Recruit ครั้งแรก
    *   **Act 2: The Journey** (Map 4-6) - ค้นหา True Hero, สร้าง Party
    *   **Act 3: The Convergence** (Map 7-9) - เตรียมการตัดสินใจสำคัญ, Romance Scene (Map 9)
    *   **Act 4: The Final Stand** (Map 10) - ต่อสู้ The Void, ตัดสินชะตากรรม
*   **Combat System (ระบบต่อสู้):**
    *   **Hybrid:** ผสมผสานระหว่าง **Classic Turn-based** และ **Dice Roll**
    *   **Defense Mechanic (Dice Roll):** เมื่อศัตรูใช้ท่าไม้ตาย (Ultimate/Special Attack) ผู้เล่นสามารถใช้ "ลูกเต๋าป้องกัน" (Defense Dice) เพื่อวัดผล:
        *   **Limited Resource:** ผู้เล่นมีลูกเต๋าป้องกันจำกัด **3 ครั้งต่อ 1 แผนที่ (Map)** การใช้จะหมดไป
        *   **Reset Condition:** จำนวนการใช้ลูกเต๋าจะรีเซ็ตกลับมาเป็น 3 ครั้งเมื่อผู้เล่นเดินทางไปยัง **แผนที่ใหม่ข้างหน้าเท่านั้น** (ไม่นับการย้อนกลับไปแผนที่เก่า)
        *   **Visual:** แสดงผลเป็น **ลูกเต๋า 3 มิติ (3D Dice)** กลิ้งบนหน้าจอ
        *   **Low Roll:** รับดาเมจเต็มๆ หรือรุนแรง (Critical Hit taken)
        *   **High Roll:** หลบหลีกได้ (Dodge) หรือลดดาเมจลง (Damage Reduction)

## 3. Roguelite Elements & Progression
*   **Permadeath:** หากตัวละครตาย ต้องเริ่มเกมใหม่ตั้งแต่ต้น
*   **Party Member Death:** เมื่อ Party Member ตาย ไม่รีเซ็ตเกม แต่มีผลต่อเนื้อเรื่อง
    *   NPC ที่ตายแล้วจะไม่ปรากฏในบทต่อๆ ไป
    *   อาจมี Quest ที่ล็อกไปหรือเปลี่ยน Ending ได้
    *   บทสนทนาใน Safe Zone เปลี่ยนไป (อื่นๆ อาจเศร้า/โกรธ)
*   **Replayability:** การเล่นแต่ละรอบอาจเจอเหตุการณ์ไม่เหมือนกัน ขึ้นอยู่กับเส้นทางที่เลือก

## 4. Narrative & Endings (เนื้อเรื่องและฉากจบ)
*   **Multiple Endings:** มีฉากจบทั้งหมด **8 แบบ**
*   **Ending Types:**
    1.  **Best Ending:** "The True Hero's Triumph" - Roran เป็น True Hero และชนะ The Void (ก่อน Day 25)
    2.  **Good Ending:** "Pyrrhic Victory" - ชนะแต่ไม่สมบูรณ์ Roran ตาย/ไม่อยู่ (ก่อน Day 30)
    3.  **Neutral Ending:** "Hollow Peace" - ชนะแบบไม่สมบูรณ์ Quest ไม่ครบ (Day 30 หรือ Day 31)
    4.  **Bad Ending:** "Eternal Darkness" - **แพ้ The Void หรือไม่สามารถกำจัดได้ก่อนวันที่ 31 = Bad Ending ทันที**
    5.  **Worst Ending:** "The Void Ascendant" - ฆ่า Roran หรือเข้าสู่ด้านมืด (3 Variants)
        - **5A:** "The Tyrant King" - ฆ่า Roran ที่ยังไม่ Awaken, ตั้งตนเป็นจอมมาร
        - **5B:** "The Fallen Hero's Betrayal" - หักหลัง Roran ที่ Awaken แล้ว, กลายเป็น New Void
        - **5C:** "The Puppet of the Void" - แพ้ Void + Corruption สูง, กลายเป็นหุ่นเชิด
    6.  **Secret Ending:** "The Liberation" - ต้องจบ Best + Worst แล้วอย่างน้อย 1 รอบ
    7.  **Sacrifice Ending:** "Bond's Salvation" - ผนึก Void ด้วย Bond Power (4 Variants)
        - **7A:** "The Hero's Sacrifice" - ผู้เล่นตายคนเดียว
        - **7B:** "Heartbroken Victory" - 3 Companions ตาย (รวม Romance Partner) ผู้เล่นรอด
        - **7C:** "Victory Through Loss" - 3 Companions ตาย (ไม่มี Romance) ผู้เล่นรอด
        - **7D:** "The Dark Survivor" - Roran ตาย, เหลือเพื่อน 2 คน, จับเพื่อนบูชายัญเพื่อรอดคนเดียว
    8.  **Escape Ending:** "The Coward's Escape" - ใช้ Chrono Crystal หนีไปอนาคต 100 ปี (ไม่สู้)
*   **Ending Factors (ปัจจัยกำหนดฉากจบ):**
    1.  **Key Choices:** การตัดสินใจครั้งสำคัญในเนื้อเรื่องหลัก (10 Key Quests)
    2.  **Karma System:** ค่าความดี/ความเลว (Good/Evil alignment)
    3.  **NPC Status:** การรอดชีวิตหรือความตายของ NPC จะส่งผลกระทบต่อเส้นเรื่อง (Butterfly Effect)
    4.  **Enemy Interactions:** การตัดสินใจสังหารหรือไว้ชีวิตศัตรูบางตัว
    5.  **Key Items:** ไอเทมสำคัญที่ปลดล็อคเส้นทางหรือความลับบางอย่าง
    6.  **Bond Level:** ความสัมพันธ์กับ Party Members (สูงสุด 100)
    7.  **Romance Choice:** เลือกคู่รักจาก 4 ตัวเลือก (Roran, Lyra, Aldric, Mara)
## 5. UI & Visual Design (การออกแบบหน้าจอ)
*   **Layout Style:** **Classic Dashboard (Dark Fantasy Theme)**
    *   **Top Bar:** แสดงสถานะผู้เล่น (Health, Mana, Gold) และค่า Stats (Strength, Dexterity, Constitution, Intelligence)
    *   **Center Visual:** พื้นที่แสดงภาพฉากและศัตรูขนาดใหญ่
    *   **Bottom Left:** กล่องข้อความ (Text Log) บนพื้นหลังกระดาษเก่า (Parchment) สำหรับเล่าเรื่อง
    *   **Bottom Right:** ปุ่มคำสั่งขนาดใหญ่ (Attack, Defend, Item)
    *   **Center Overlay:** เอฟเฟกต์ลูกเต๋า 3D (d20) ลอยขึ้นมากลางหน้าจอเมื่อมีการวัดผล

## 6. Character Stats System (ระบบค่าสถานะ)

### Leveling System
*   **Experience Currency:** Souls/Essence ได้จากการฆ่าศัตรู ใช้สำหรับ Leveling Up
*   **Stat Points per Level:** +4 Stat Points ต่อการอัพเลเวล (ลดจาก 5)
*   **Max Level:** 100
*   **Stat Cap:** ทุก Stat มี Cap สูงสุด = 100
*   **Total Points Available:** 100 Level × 4 Points = 400 Total Points (ต้องเลือก Focus บาง Stat)

### Primary Stats (ส่งผลต่อเงื่อนไขการสวมใส่อุปกรณ์ Unique)
*   **Strength (STR):**
    *   เพิ่มดาเมจการโจมตีปกติ (Physical Damage) +2% DMG per STR
    *   เพิ่มขีดจำกัดการแบกของ (Inventory Capacity)
    *   ใช้ผ่านสถานการณ์ที่ต้องใช้พละกำลัง (Force Actions)
*   **Dexterity (DEX):**
    *   เพิ่มโอกาสหลบหลีก (Dodge Chance) +1% per DEX
    *   เพิ่มความแม่นยำ (Accuracy) +1% per DEX
    *   ได้ Initiative ในการต่อสู้ (ไปก่อนศัตรู)
*   **Constitution (CON):**
    *   เพิ่มเลือดสูงสุด (Max HP) +2 HP per CON
    *   ลดดาเมจที่ได้รับ (Damage Reduction) +0.5% per CON
*   **Intelligence (INT):**
    *   เพิ่มมานาสูงสุด (Max Mana) +2 Mana per INT
    *   เพิ่มดาเมจเวทมนตร์ (Magic Damage) +2% DMG per INT
    *   **Narrative Effect:** ปลดล็อคตัวเลือกพิเศษ (INT > 50 = ตัวเลือก Analytical/Insightful), ช่วยไขปริศนา (INT > 80 = ได้คำใบ้)

### Secondary Stats (สายสนับสนุน)
*   **Luck (LUK):**
    *   เพิ่มโอกาสชนะในการเสี่ยงดวง (Gambling/Random Events) +1% per LUK
    *   ลดผลกระทบและความรุนแรงจากสถานะผิดปกติ (Debuff Resistance) +0.5% per LUK
*   **Faith (FAI):**
    *   เพิ่มประสิทธิภาพและระยะเวลาของบัฟ (Buff Effectiveness & Duration) +1% per FAI
    *   เพิ่มโอกาสติดคริติคอล (Critical Rate) +0.5% per FAI

## 7. Additional Systems (ระบบเพิ่มเติม)
*   **Map & Navigation (การเดินทาง):**
    *   **Pure Text Choices:** การสำรวจหลักใช้การเลือกเส้นทางผ่านข้อความ (ซ้าย/ขวา/สำรวจ)
    *   **Mini-map:** มีแผนที่ภาพรวมของโซนนั้นๆ ให้ดู เพื่อให้ผู้เล่นรู้ตำแหน่งคร่าวๆ ของ **Boss** และ **Village (Safe Zone)**
    *   **Checkpoint System (จุดวาร์ป):** ในแต่ละแผนที่จะมี Checkpoint 1-2 จุด เมื่อผู้เล่นไปถึงและเปิดใช้งานแล้ว จะสามารถใช้เดินทางเร็ว (Fast Travel) ระหว่าง Checkpoint ที่เคยเปิดใช้งานทั้งหมดได้
        *   **Important:** ระบบนี้ใช้เพื่อการเดินทางเท่านั้น **ไม่ใช่ระบบ Save/Load** (เกมยังคงเป็น Permadeath)
        *   ไม่สามารถวาร์ปไปยัง Checkpoint ที่ยังไม่เคยไปถึงได้
    *   **Dynamic Weather/Time System:** บางโซนเปลี่ยนตามเวลา (Night → Harder Enemies, Day → Safe Zones Open)
*   **Inventory System (ช่องเก็บของ):**
    *   **Slot-based:** จำกัดจำนวนช่องเก็บของ (เช่น เริ่มต้น 20 ช่อง) ของ 1 ชิ้นใช้ 1 ช่อง ง่ายต่อการจัดการ
    *   **Item Durability:** อุปกรณ์ใช้งานแล้วทำให้ Durability ลดลง ต้องซ่อมในเมือง
*   **Progression (การพัฒนาตัวละคร):**
    *   **Skill Tree:** เมื่อเลเวลอัพจะได้แต้ม Skill Points มาอัพเกรดสกิลในสายต่างๆ (ดูรายละเอียดใน `skill_tree.md`)
    *   **Bond Level:** Party Member แต่ละคนมี Bond Level (ไม่เสีย stat, เพียงแต่ unlock Combo Attack และเพิ่ม Dodge Chance)
*   **Camping & Crafting (การพักแรมและสร้างของ):**
    *   **Resting:** จุดพักเพื่อฟื้นฟู HP/Mana และเพิ่มประสิทธิภาพในด่านถัดไป
    *   **Crafting/Cooking:** สามารถปรุงยา (Potions) หรือทำอาหาร (Food) เพื่อบัฟสถานะได้
    *   **Trading:** ในหมู่บ้านหรือจุดพักบางแห่งจะมี NPC พ่อค้าให้ซื้อขายไอเทม
*   **Resource Tension:**
    *   Gold และ Souls หายากขึ้น ต้องเลือกว่าจะ Buy Potion หรือ Upgrade Skill

## 8. Extended Mechanics & World Building (ระบบเชิงลึก)
*   **Character Creation (การสร้างตัวละคร):**
    *   **Class System (7 Classes):** เลือกอาชีพเริ่มต้น ซึ่งจะกำหนด Stats เริ่มต้น (10 points) และอุปกรณ์ติดตัว
    
    #### 7 Class Specifications:
    
    **1. Knight (อัศวิน) - Tank/Defender**
    - Starting Stats: STR 12, DEX 6, CON 14, INT 4, LUK 3, FAI 5
    - Strong vs: Aerial (ground), Humanoid, Beast
    - Weak vs: Ethereal, Formless, Casters
    - Skills: Defensive Stance, Shield Bash, Heavy Blow
    
    **2. Mage (มักษ์) - Ranged Magic/AOE**
    - Starting Stats: STR 3, DEX 7, CON 5, INT 15, LUK 4, FAI 6
    - Strong vs: Formless, Elementals, Groups
    - Weak vs: Tanks, Assassins, Magic-Immune
    - Skills: Fireball, Ice Shard, Mana Shield
    
    **3. Rogue (โร้ก) - Speed/Crit**
    - Starting Stats: STR 8, DEX 14, CON 6, INT 5, LUK 9, FAI 3
    - Strong vs: Speed-types, Constructs (weak points), Bosses (kiting)
    - Weak vs: Armor tanks, Projectiles, Heavy Hitters
    - Skills: Double Strike, Evasion, Poison Coat
    
    **4. Paladin (พลาดิน) - Holy Hybrid/Support**
    - Starting Stats: STR 10, DEX 8, CON 10, INT 10, LUK 5, FAI 12
    - Strong vs: Dark/Undead, Mixed Threats, Group Support
    - Weak vs: Extreme Specialists, Speed Race
    - Skills: Holy Smite, Blessing, Divine Shield
    
    **5. Ranger (เรนเจอร์) - Ranged Physical/Utility**
    - Starting Stats: STR 9, DEX 12, CON 8, INT 7, LUK 10, FAI 4
    - Strong vs: Flying, Distant Casters, Boss Kiting
    - Weak vs: Close Rushers, Heavy Armor, Mana-Limited
    - Skills: Power Shot, Rain of Arrows, Track Beast
    
    **6. Warlock (วอร์ล็อก) - Dark Magic/Corruption**
    - Starting Stats: STR 4, DEX 6, CON 7, INT 14, LUK 5, FAI 8
    - Strong vs: Holy/Divine, High HP Bosses, Secret Routes
    - Weak vs: Paladins, Physical Rushers, Mana Drain
    - Skills: Dark Bolt, Plague Cloud, Eldritch Bargain
    
    **7. Shaman (ชาแมน) - Support/Elemental**
    - Starting Stats: STR 6, DEX 8, CON 9, INT 11, LUK 8, FAI 13
    - Strong vs: Environmental, Long Fights, Mixed Groups
    - Weak vs: One-shots, Silence, Pure Damage, Speedrunners
    - Skills: Heal Over Time, Totem Placement, Elemental Surge

*   **Economy (เศรษฐกิจ):**
    *   **Dual Currency:**
        *   **Gold:** ใช้ซื้อไอเทม, อาหาร, และอุปกรณ์จากร้านค้า
        *   **Souls/Essence:** แต้มที่ได้จากการฆ่าศัตรู ใช้สำหรับ Leveling Up Stats & Skills (ดรอบจาก Monster แต่ได้น้อย)
*   **Monster Drop System:**
    *   **Resource Tension:** ได้ Gold/Souls จากศัตรู แต่ไม่มากพอ ต้องเลือกว่าจะใช้ทำไห
    *   Low-tier Monster: 10 Gold, 5 Souls
    *   Mid-tier Monster: 50 Gold, 25 Souls
    *   High-tier Monster/Boss: 200 Gold, 100 Souls
*   **Corruption/Sanity System:**
    *   ค่า Corruption เพิ่มขึ้นเมื่อ สวมใจ Dark Magic หรือทำสิ่งที่ "ผิดจริยธรรม"
    *   ถ้า Corruption สูงเกินไป → ปลดล็อก Dark Ending หรือ Transformation ที่เปลี่ยน Stats
*   **Quest Structure (โครงสร้างเควส):**
    *   **Main & Side Quests:** มีเควสหลักดำเนินเรื่อง และเควสย่อยจากชาวบ้าน
    *   **Impactful Side Quests:** เควสย่อยบางอันมีความสำคัญมาก หากทำสำเร็จ/ล้มเหลว จะส่งผลกระทบต่อเนื้อเรื่องหลักและฉากจบ (Ending)
    *   **Time Management:** การใช้เวลาอย่างชาญฉลาด เพราะมีเวลาจำกัด 30 วัน
*   **Enemy System (ความลึกของศัตรู):**
    *   **8 Monster Types:** (ดูรายละเอียดใน `monster type.md`)
        1. **HUMANOID** - Parry/Counter (Knight/Rogue strong)
        2. **BEAST** - Bleed mechanic (Ranger/Rogue strong)
        3. **AERIAL** - Fly evasion (Knight/Ranger strong)
        4. **UNDEAD** - Poison immune (Paladin/Warlock strong)
        5. **FORMLESS** - Physical immunity (Mage/Warlock strong)
        6. **ELEMENTAL** - Opposite weakness (Mage/Shaman strong)
        7. **PLANT** - Regen/multi-part (Ranger/Warlock strong)
        8. **CONSTRUCT** - Weak points (Rogue/Mage strong)
    *   **Monster Tier System:** Monsters มี Tier ระดับ 1-13 (ไม่มี Boss อยู่ใน Tier)
        - **Tier 1-3:** Early Zone Monsters (Weak)
        - **Tier 4-6:** Early-Mid Zone Monsters
        - **Tier 7-9:** Mid Zone Monsters
        - **Tier 10-12:** Late Zone Monsters (Strong)
        - **Tier 13:** Extremely Rare/Endgame Monsters (Pre-Boss)
        - **Boss:** พิเศษ ไม่อยู่ใน Tier System
    *   **Monster Distribution:** 250 General Monsters กระจายตาม 10 Maps (ดูรายละเอียดใน `monster_distribution.md`)
    *   **Night Raid System:** (เริ่มตั้งแต่วันที่ 10)
        - Day 10-14: First Raids (Tier 3-4, 1 Wave)
        - Day 15: Double Trouble (Tier 5-6, 2 Waves)
        - Day 20: Void Incursion (Tier 8-9, Void Minions)
        - Day 25: Void Onslaught (Tier 10-11, 2 Waves)
        - Day 26-29: Total Despair (Tier 12+, Mixed)
    *   **Special Traits:** Regeneration, Poison Spit, Pack Mentality, Last Stand, Adaptation, Summon, Berserk
*   **Party System (ระบบปาร์ตี้):**
    *   **7 Recruitable Characters:**
        1.  **RORAN** (Knight ♂) - True Hero, มี Key Quest KQ-01 + KQ-10, Romance Candidate
        2.  **LYRA** (Rogue ♀) - มี Key Quest KQ-02, Romance Candidate
        3.  **KAEL** (Ranger ♂) - มี Recruitment Quest (ไม่ใช่ Key Quest), Not Romance
        4.  **ALDRIC** (Paladin ♂) - มี Key Quest KQ-04, Romance Candidate
        5.  **MARA** (Warlock ♀) - มี Key Quest KQ-05, Romance Candidate
        6.  **THERON** (Shaman ♂) - ไม่มี Key Quest, Not Romance
        7.  **CASSIA** (Sky Captain ♀) - เกี่ยวข้อง KQ-08, Not Romance
    *   **Bond & Recruitment:** สร้างความสัมพันธ์กับ NPC จนถึงระดับหนึ่งเพื่อชวนเข้าปาร์ตี้
    *   **Resonance/Bond Meter:** ยิ่ง Bond สูง → Unlock Combo Attack, เพิ่ม Dodge Chance เมื่อสมาชิกอยู่ข้าง
    *   **Full Control:** ผู้เล่นสามารถควบคุมตัวละครในปาร์ตี้ได้ทุกตัวในฉากต่อสู้ (เลือกท่าโจมตี/ใช้ไอเทมได้เหมือนตัวหลัก)
    *   **Romance System (ระบบความรัก):**
        *   **4 Romance Candidates:** Roran, Lyra, Aldric, Mara (ทั้งหมดมี Key Quest)
        *   **Unlock:** ต้องมี Bond Level MAX (100) + ทำ Key Quest ครบ + ถึง Map 9
        *   **Romance Scenes:** ฉากพิเศษที่ Map 9 ก่อนการต่อสู้ครั้งสุดท้าย
        *   **Impact:** ส่งผลต่อ Ending 7 (Bond's Salvation) และบทสนทนาพิเศษ

## 9. Meta-Progression & World Detail (รายละเอียดเชิงลึก)
*   **Legacy System (ระบบสืบทอด):**
    *   **Heirloom:** ผู้เล่นสามารถฝากไอเทมไว้ใน "คลังสมบัติ" (Vault) ได้ 1 ชิ้นก่อนจบเกมหรือก่อนตาย เพื่อให้ตัวละครตัวถัดไป (New Run) สามารถหยิบไปใช้ได้ทันที
*   **Map Structure (โครงสร้างแผนที่):**
    *   **10 Zones/Maps:**
        1.  Map 1: Ashwood Settlement (เริ่มต้น)
        2.  Map 2: Ravine Pass
        3.  Map 3: Wetland Marshes
        4.  Map 4: Stone Kingdom Ruins
        5.  Map 5: Bleeding Forest
        6.  Map 6: Obsidian Caverns
        7.  Map 7: Desolate Wastes
        8.  Map 8: Shattered Isles
        9.  Map 9: Nightfall Valley (Romance Unlock)
        10. Map 10: The Void's Gates (Final Boss)
    *   **30-Day Time Limit:** ผู้เล่นมีเวลา 30 วันในการสำรวจและเตรียมพร้อม
    *   **Time Pressure:** The Void แข็งแกร่งขึ้นทุกวัน, Monster Tier เพิ่มขึ้น
*   **Quest Structure (โครงสร้างเควส):**
    *   **Main & Side Quests:** 
        *   **10 Key Quests (KQ-01 to KQ-10):** เควสหลักดำเนินเรื่อง, ส่งผลต่อ Ending
        *   **50 Side Quests:** 30 General Quests + 20 Monster Hunts
        *   **30 NPCs:** ตัวละครทั่วไปที่ให้เควสและเพิ่มความลึกให้โลก
    *   **Impactful Side Quests:** เควสย่อยบางอันมีความสำคัญมาก หากทำสำเร็จ/ล้มเหลว จะส่งผลกระทบต่อเนื้อเรื่องหลักและฉากจบ (Ending)
    *   **Key Quest Examples:**
        *   **KQ-01:** The Blacksmith's Debt (Roran's recruitment)
        *   **KQ-02:** Mercy for the Thief (Lyra's recruitment)
        *   **KQ-04:** The Lapsed Priest (Aldric's recruitment)
        *   **KQ-05:** The Cursed Huntress (Mara's recruitment)
        *   **KQ-08:** The Sky Pirate's Mutiny (Cassia's recruitment)
        *   **KQ-10:** The Hero's Test (Roran revealed as True Hero)
*   **Lore & Characters (เนื้อเรื่องและตัวละคร):**
    *   **Protagonist:** ผู้เล่นเลือก Class จาก 7 อาชีพ
    *   **World Setting:** โลก Aeloria กำลังถูก The Void คุกคาม
    *   **The Void:** พลังมืดที่กลืนกินโลก มีเวลา 30 วัน ก่อนโลกจะถูกทำลายสิ้น
    *   **True Hero Mystery:** Roran เป็น True Hero แต่ผู้เล่นต้องค้นพบด้วยตัวเอง

## 10. Next Steps (สิ่งที่ต้องทำต่อ)
*   [x] Brainstorm รายละเอียด Lore, Map (Zone System) และ Party Members
*   [x] ออกแบบ NPC Characters พร้อม Bond/Recruitment mechanics
*   [x] ออกแบบ Romance System (4 Candidates)
*   [x] กำหนด Ending System (8 Endings)
*   [x] ออกแบบ Quest Structure (10 Key + 50 Side Quests)
*   [x] สร้าง Monster Database (8 Types, Tier 1-13, 250 Monsters)
*   [x] ออกแบบ Night Raid System (Day 10-29)
*   [ ] เริ่มเขียน Code โครงสร้างหน้าเว็บ (HTML/CSS/React)
*   [ ] ร่าง Flow ของเนื้อเรื่องบทแรก
*   [x] ออกแบบ Skill Tree สำหรับทั้ง 7 Class
*   [ ] ออกแบบ UI/UX สำหรับ Romance Scenes
*   [x] ออกแบบ Boss Encounters (10 Maps + Final Boss)