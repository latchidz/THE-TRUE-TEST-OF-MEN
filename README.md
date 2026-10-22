# 🎬 THE TRUE TEST OF MEN — STEP 3 PACK
## الشدة تبين الرجال

**12 مشهد · 26 إطار · 14 مقطع · 10 ثواني لكل مقطع · 2:20**

---

# 📁 التنظيم

```
THE_TRUE_TEST_OF_MEN_STEP3/
│
├── PROMPTS/                   ← كل البرومبتات مجموعة في مجلد واحد
│   ├── PROMPT_01_SCENE_01_A.md
│   ├── PROMPT_02_SCENE_01_B.md
│   ├── PROMPT_03_SCENE_02.md
│   ├── PROMPT_04_SCENE_03_A.md
│   ├── PROMPT_05_SCENE_03_B.md
│   ├── PROMPT_06_SCENE_04.md
│   ├── PROMPT_07_SCENE_05.md
│   ├── PROMPT_08_SCENE_06.md
│   ├── PROMPT_09_SCENE_07.md
│   ├── PROMPT_10_SCENE_08.md
│   ├── PROMPT_11_SCENE_09.md
│   ├── PROMPT_12_SCENE_10.md
│   ├── PROMPT_13_SCENE_11.md
│   ├── PROMPT_14_SCENE_12.md
│   └── ALL_PROMPTS.md          ← الـ14 في ملف واحد
│
└── SCENES/                    ← كل مشهد في مجلد خاص بيه
    ├── SCENE_01/  ← المشهد الأول
    │   ├── S01a_OFFICE_WIDE.png
    │   ├── S01b_FATHER_BREAKS.png
    │   └── S01c_HANDS.png
    ├── SCENE_02/
    │   ├── S02a_ROAD_WALKING.png
    │   └── S02b_SHOP_DOOR.png
    ├── SCENE_03/
    │   ├── S03a_PERFUME_ENTER.png
    │   ├── S03b_YOUSSEF_FACE.png
    │   └── S03c_LEAVING.png
    ├── SCENE_04/  S04a · S04b
    ├── SCENE_05/  S05a · S05b
    ├── SCENE_06/  S06a · S06b
    ├── SCENE_07/  S07a · S07b
    ├── SCENE_08/  S08a · S08b
    ├── SCENE_09/  S09a · S09b
    ├── SCENE_10/  S10a · S10b
    ├── SCENE_11/  S11a · S11b
    └── SCENE_12/  S12a · S12b
```

**القاعدة:** كل برومبت يشير لصور مشهدو بالمسار `../SCENES/SCENE_XX/`.

---

# 🗂️ خريطة المشاهد

| # | المجلد | العنوان | المكان | الإطارات | المقاطع |
|---|---|---|---|---|---|
| **01** | `SCENE_01` | THE ULTIMATUM — الإنذار | مكتب الطبيب | 3 | 2 |
| **02** | `SCENE_02` | THE ROAD — الطريق | الشارع | 2 | 1 |
| **03** | `SCENE_03` | FIRST CLOSED DOOR — يوسف | محل العطور | 3 | 2 |
| **04** | `SCENE_04` | SECOND CLOSED DOOR — رامي | الورشة | 2 | 1 |
| **05** | `SCENE_05` | THIRD CLOSED DOOR — كريم | محل الهواتف | 2 | 1 |
| **06** | `SCENE_06` | FOURTH CLOSED DOOR — حمزة | البقالة | 2 | 1 |
| **07** | `SCENE_07` | THE BREAKING POINT — الانكسار | الشارع · الغروب | 2 | 1 |
| **08** | `SCENE_08` | THE PRICE — الثمن | مكتب الطبيب · ليل | 2 | 1 |
| **09** | `SCENE_09` | THE DOOR OPENS — الباب | قاعة الانتظار | 2 | 1 |
| **10** | `SCENE_10` | THE ENVELOPE — الظرف | قاعة الانتظار | 2 | 1 |
| **11** | `SCENE_11` | THE EMBRACE — العناق | قاعة الانتظار | 2 | 1 |
| **12** | `SCENE_12` | THE WAIT — الانتظار | قاعة الانتظار · 02:20 | 2 | 1 |

---

# ⚙️ إعدادات Flow (لكل مقطع)

```
Model ........ Veo 3.1 Fast
Mode ......... Video  >  Frames  >  First and last
Aspect ....... 9:16
Duration ..... 10 s
Audio ........ OFF          (الصوت يُبنى في المونتاج)
Outputs ...... 2
Ingredients .. 3 max
```

---

# 🔗 السلسلة — 14 مقطع

| # | وجهة البرومبت | FIRST | LAST |
|---|---|---|---|
| 01 | `PROMPT_01_SCENE_01_A` | `SCENE_01/S01a_OFFICE_WIDE.png` | `SCENE_01/S01b_FATHER_BREAKS.png` |
| 02 | `PROMPT_02_SCENE_01_B` | `SCENE_01/S01b_FATHER_BREAKS.png` | `SCENE_01/S01c_HANDS.png` |
| 03 | `PROMPT_03_SCENE_02` | `SCENE_02/S02a_ROAD_WALKING.png` | `SCENE_02/S02b_SHOP_DOOR.png` |
| 04 | `PROMPT_04_SCENE_03_A` | `SCENE_03/S03a_PERFUME_ENTER.png` | `SCENE_03/S03b_YOUSSEF_FACE.png` |
| 05 | `PROMPT_05_SCENE_03_B` | `SCENE_03/S03b_YOUSSEF_FACE.png` | `SCENE_03/S03c_LEAVING.png` |
| 06 | `PROMPT_06_SCENE_04` | `SCENE_04/S04a_WORKSHOP_DRAWER.png` | `SCENE_04/S04b_DRAWER_SHUT.png` |
| 07 | `PROMPT_07_SCENE_05` | `SCENE_05/S05a_PHONE_SHOP.png` | `SCENE_05/S05b_KARIM_NO.png` |
| 08 | `PROMPT_08_SCENE_06` | `SCENE_06/S06a_GROCERY.png` | `SCENE_06/S06b_HAMZA_NO.png` |
| 09 | `PROMPT_09_SCENE_07` | `SCENE_07/S07a_STREET_STANDING.png` | `SCENE_07/S07b_STREET_CRYING.png` |
| 10 | `PROMPT_10_SCENE_08` | `SCENE_08/S08a_THE_PRICE.png` | `SCENE_08/S08b_THE_HAND.png` |
| 11 | `PROMPT_11_SCENE_09` | `SCENE_09/S09a_DOOR_OPENS.png` | `SCENE_09/S09b_FOUR_MEN_RISE.png` |
| 12 | `PROMPT_12_SCENE_10` | `SCENE_10/S10a_THE_ENVELOPE.png` | `SCENE_10/S10b_TAKING_IT.png` |
| 13 | `PROMPT_13_SCENE_11` | `SCENE_11/S11a_THE_EMBRACE.png` | `SCENE_11/S11b_FIVE_MEN.png` |
| 14 | `PROMPT_14_SCENE_12` | `SCENE_12/S12a_THE_WAIT.png` | `SCENE_12/S12b_END.png` |

> **القاعدة:** LAST FRAME N = FIRST FRAME N+1 داخل نفس المشهد ⇒ بلا قطع.
> بين المشاهد ⇒ **قطع** (سينما).

---

# 📄 كل برومبت فيه

| # | القسم |
|---|---|
| 1 | إعدادات Flow |
| 2 | الإطاران (FIRST / LAST) + وصف كل واحد |
| 3 | MASTER STYLE — الجمالية الموحدة |
| 4 | FACE LOCK + GAZE LOCK |
| 5 | MOTION PROMPT — النص اللي تلصقو |
| 6 | Foley — الصوت |
| 7 | الحوار بالدارجة + ترجمة |
| 8 | NEGATIVE + CHECK list |

---

# 🔒 القوانين المطبّقة

| القانون | واش يفرض |
|---|---|
| **FACE = REFERENCE** | لحية أمين قصيرة تنتهي عند الذقن · بلا مبالغة في حتى ملمح |
| **GAZE LOCK** | حتى واحد ما ينظر للكاميرا — الكاميرا مُلاحِظ خفي |
| **YOUSSEF** | النظارات السوداء على وجهو دايماً |
| **PROP** | الملف الطبي في يد أمين · الظرف A4 مسدود (ماشي ساك) |
| **STYLE** | 35mm · Portra 400 / Cinestill 800T · بلا CGI · بلا موسيقى |

---

*THE TRUE TEST OF MEN · STEP 3 · 2026-10-22*
