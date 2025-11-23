# Game Balance Calculation: Stats, Souls & Progression

เอกสารนี้คำนวณความสมดุลของระบบเลเวล (1-100), ค่าสถานะ (Stats), และเศรษฐกิจของ Souls (Experience) เพื่อให้เกมมีความท้าทายแต่เป็นไปได้จริงภายในเวลา 30 วัน

---

## 1. Stat Progression (ระบบค่าสถานะ)

### Core Data
*   **Max Level:** 100
*   **Stat Points per Level:** 4
*   **Total Earned Points:** 400 Points (ที่ Level 100)
*   **Starting Stats:** ~40 Points (กระจายตาม Class)
*   **Grand Total Points:** ~440 Points
*   **Stat Cap (Max):** 99 (เพื่อให้สอดคล้องกับ Skill Requirement สูงสุด)

### Analysis & Milestones
เนื่องจากผู้เล่นมีแต้มรวม ~440 และ Stat Cap คือ 99 หมายความว่าผู้เล่นสามารถ **Max ได้ถึง 4 Stats** (จาก 6 Stats: STR, DEX, CON, INT, FAI, LUK) หากเล่นจนถึงเลเวล 100
*   *Design Note:* เลเวล 100 คือสถานะ "Demigod" หรือ "Awakened Hero" ที่เก่งมากๆ เหมาะสำหรับสู้กับ True Void

#### Progression Curve (การเติบโตของตัวละคร)
| Level | Total Points | Build Status | Skill Tier Access |
| :-- | :-- | :-- | :-- |
| **Lv 1** | 0 (+Base) | **Novice:** ค่าสถานะต่ำมาก เน้นเอาตัวรอด | Tier 1 |
| **Lv 20** | 80 | **Specialist:** เริ่ม Max ได้ 1 Stat (เช่น STR 80) หรือเกลี่ยๆ | Tier 5 (Ult ต้นเกม) |
| **Lv 40** | 160 | **Expert:** Max 1 Stat (99) + รอง 1 Stat (60) | Tier 8 |
| **Lv 60** | 240 | **Master:** Max 2 Stats (99, 99) + กันตาย (CON 40) | Tier 10 |
| **Lv 80** | 320 | **Legend:** Max 3 Stats (99, 99, 99) | Tier 11 |
| **Lv 100** | 400 | **Demigod:** Max 4 Stats (Perfect Build) | Tier 12 (Ultimate) |

---

## 2. Soul Economy (ระบบโซลและเลเวล)

เพื่อให้ผู้เล่นไปถึง Lv 60-80 ในการเล่นปกติ (Normal Run) และ Lv 100 ในการเล่นที่สมบูรณ์แบบ (Perfect Run/Farming) ภายใน 30 วัน (จำกัด Action)

### XP Curve Formula (สูตรคำนวณ)
เราจะใช้กราฟแบบ **Exponential (Growth 1.08)** เพื่อให้ช่วงต้นไวและช่วงปลายยาก
*   **สูตร:** `Next Level XP = Base_XP * (Level ^ 1.8)`
*   **Base XP:** 50

#### XP Table (ตัวอย่าง)
| Level Range | XP Needed (ต่อเลเวล) | Cumulative XP (รวม) | หมายเหตุ |
| :-- | :-- | :-- | :-- |
| **1 -> 10** | 50 - 3,000 | ~15,000 | ช่วง Tutorial (Day 1-3) |
| **11 -> 30** | 3,500 - 22,000 | ~250,000 | ช่วง Early Game (Day 4-10) |
| **31 -> 60** | 23,000 - 80,000 | ~1,800,000 | ช่วง Mid Game (Day 11-20) |
| **61 -> 90** | 82,000 - 160,000 | ~5,500,000 | ช่วง Late Game (Day 21-28) |
| **91 -> 100** | 165,000 - 200,000 | **~7,500,000** | ช่วง Final Grind (Day 29-30) |

**สรุป:** ผู้เล่นต้องหา Souls รวมประมาณ **7.5 ล้าน Souls** เพื่อจบที่ Lv 100

---

## 3. Monster Drop Balance (การดรอปโซล)

ต้องกำหนดให้สอดคล้องกับ XP Table โดยคำนึงว่าผู้เล่นมีเวลาจำกัด (Movement Action)
*   **Assumption:** 1 วัน = 10 Movements
*   **Encounters per Day:** เฉลี่ย 5-8 การต่อสู้ (1 Fight อาจมีมอนสเตอร์ 1-3 ตัว)
*   **Total Fights (30 Days):** ~200 Encounters (ประมาณ 500-600 ตัว)

#### Soul Drop Rates by Tier
| Monster Tier | Avg. Souls / Kill | Est. Kills for 1 Level | Difficulty Context |
| :-- | :-- | :-- | :-- |
| **Tier 1** (Rat, Slime) | **50** | 2-5 ตัว | ง่ายมาก (One shot) |
| **Tier 2** (Wolf, Bandit) | **120** | 5-10 ตัว | เริ่มต้องใช้สกิล |
| **Tier 3** (Bear, Skeleton) | **300** | 10-15 ตัว | มอนสเตอร์เลเวล 10+ |
| **Tier 4** (Orc, Ghoul) | **600** | 15-20 ตัว | เริ่มตึงมือ |
| **Tier 5** (Troll, Wraith) | **1,200** | 20 ตัว | Mid Game Standard |
| **Tier 6** (Griffon, Knight) | **2,500** | 15-20 ตัว | ให้ XP เยอะขึ้นก้าวกระโดด |
| **Tier 7** (Drake, Lich) | **5,000** | 10-15 ตัว | Late Game Start |
| **Tier 8** (Golem, Demon) | **10,000** | 8-10 ตัว | High Risk |
| **Tier 9** (Wyvern, Elder) | **20,000** | 5-8 ตัว | Very High XP |
| **Tier 10** (Void Beast) | **40,000** | 3-5 ตัว | Late Game Farming |
| **Tier 11** (Void Elite) | **80,000** | 2-3 ตัว | เกือบ 1 เลเวลต่อตัว |
| **Tier 12** (Void Lord) | **150,000** | 1 ตัว = 1 เลเวล | Mini-Boss |
| **Tier 13** (Guardian) | **300,000** | 1 ตัว = 2 เลเวล | Rare Encounter |
| **BOSS (Map Boss)** | **500,000** | Instant 3-5 Levels | รางวัลใหญ่จบแมพ |

---

## 4. Simulation: The 30-Day Journey (จำลองการเล่น)

ลองคำนวณว่าถ้าผู้เล่นเล่นแบบ **"เก่งแต่ไม่โกง"** (Good Play) จะจบที่เลเวลเท่าไหร่

### Phase 1: The Beginning (Day 1-5)
*   **Target:** Map 1-2 (Tier 1-3)
*   **Activity:** ฆ่า Tier 1-2 ประมาณ 50 ตัว + Boss Map 1
*   **Souls Earned:** (50 * 100) + 100,000 (Boss/Quest) = ~105,000 Souls
*   **Result:** **Level 15-18**
*   **Stats:** 60-70 Points (เริ่มอัพสกิล Tier 4 ได้)

### Phase 2: The Journey (Day 6-15)
*   **Target:** Map 3-5 (Tier 4-6)
*   **Activity:** ฆ่า Tier 4-6 ประมาณ 100 ตัว + Boss Map 3 & 4
*   **Souls Earned:** (100 * 1,500) + 500,000 (Bosses) = ~650,000 Souls
*   **Cumulative:** ~755,000 Souls
*   **Result:** **Level 40-45**
*   **Stats:** 160-180 Points (เริ่ม Max 1 Stat ได้แล้ว / Tier 8 Unlocked)

### Phase 3: The Convergence (Day 16-25)
*   **Target:** Map 6-8 (Tier 7-9)
*   **Activity:** ฆ่า Tier 7-9 ประมาณ 80 ตัว + Night Raids (Bonus XP)
*   **Souls Earned:** (80 * 15,000) + 1,000,000 (Raids/Bosses) = ~2,200,000 Souls
*   **Cumulative:** ~3,000,000 Souls
*   **Result:** **Level 70-75**
*   **Stats:** 280-300 Points (Max 2 Stats + Survival / Tier 11 Unlocked)

### Phase 4: The Final Grind (Day 26-30)
*   **Target:** Map 9-10 (Tier 10-13)
*   **Activity:** ฆ่า Tier 10-13 (Void Monsters) ประมาณ 50 ตัว + Boss Map 9
*   **Souls Earned:** (50 * 80,000) + 1,000,000 = ~5,000,000 Souls
*   **Cumulative:** ~8,000,000 Souls
*   **Result:** **Level 98-100**
*   **Stats:** 390-400 Points (Max 3-4 Stats / Tier 12 Ultimate Unlocked)

---

## 5. Conclusion (สรุปความสมดุล)
*   **Level 100 เป็นไปได้:** หากผู้เล่นขยันฟาร์มมอนสเตอร์ Tier สูงในช่วงท้ายเกม (Day 26+)
*   **Casual Player:** น่าจะจบที่ **Level 60-70** (ปลดล็อคสกิล Tier 10) ซึ่งเพียงพอสำหรับจบเกมแบบ Normal/Good Ending
*   **Hardcore Player:** จะจบที่ **Level 90-100** (ปลดล็อค Ultimate) ซึ่งจำเป็นสำหรับ **True Hero Ending** หรือสู้กับ **Secret Boss**
*   **Stat Strategy:**
    *   ช่วงแรก (Lv 1-40): ต้องโฟกัส 1 Stat เพื่อปลดล็อคสกิลสายหลัก
    *   ช่วงกลาง (Lv 41-70): เริ่มอัพ Stat รอง หรือ CON เพื่อความอึด
    *   ช่วงท้าย (Lv 71-100): Max Stat ที่ 3 หรือ 4 เพื่อความสมบูรณ์แบบ
