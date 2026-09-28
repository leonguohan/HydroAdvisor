# HydroAdvisor
Science-backed daily hydration plans tailored to your body, activity &amp; lifestyle

# 💧 HydroAdvisor

> A science-backed, personalized daily hydration planner that optimizes physical endurance, cognitive focus, and daily energy — all running client-side with zero dependencies.

---

## ✨ Features

- **5-Step Guided Intake** — Collects biometrics, activity, schedule, and lifestyle data through an interactive form
- **Smart Calculation Engine** — Computes your daily fluid target using weight-based baselines, activity add-ons, climate multipliers, and lifestyle offsets
- **Phase-by-Phase Schedule** — Breaks your daily intake into time-aligned blocks (morning activation, focus blocks, workout recovery, evening wind-down)
- **Cognitive Focus Timing** — Strategically times hydration around deep work and afternoon energy slumps
- **Electrolyte Alerts** — Automatically triggered when workouts exceed 60 min, intensity is high, or a keto diet is selected
- **Focus Score** — A composite 0–100 rating reflecting how well your plan supports mental clarity
- **Zero Backend** — Pure HTML + CSS + JavaScript; works offline, no server required

---

## 🚀 Getting Started

Just open the file in any modern browser — no install, no build step needed.

```bash
git clone https://github.com/leonguohan/HydroAdvisor.git
cd HydroAdvisor
open index.html
```

---

## 🧮 Calculation Logic

| Factor | Method |
|---|---|
| **Baseline** | `weight (kg) × 33 ml`, adjusted for biological sex and age |
| **Activity add-on** | `(duration / 60) × intensity factor` — ranges 250–800 ml/hr |
| **Climate multiplier** | Up to +25% for tropical or dry-heat environments |
| **Caffeine offset** | +35 ml per cup/day to counteract diuretic effect |
| **Diet adjustment** | +400 ml for keto/low-carb (glycogen/sodium flush) |
| **Special status** | +300 ml pregnant · +450 ml nursing · +150–300 ml alcohol |

---

## 📋 Input Parameters

- **Biometrics** — Weight, height, age, biological sex, health flags (pregnant, nursing, fluid restriction)
- **Activity** — Workout type(s), duration, days/week, intensity level
- **Environment** — Climate (tropical, dry, temperate, cold, indoor AC)
- **Schedule** — Wake time, bedtime, deep focus blocks, afternoon slump timing
- **Lifestyle** — Caffeine intake, alcohol frequency, dietary pattern

---

## ⚠️ Health Disclaimer

This tool is for informational and wellness optimization purposes only and does not constitute medical advice. Individuals with kidney conditions, cardiovascular disease, heart failure, or specific medical fluid restrictions should consult a healthcare provider before following any recommendations from this planner.

---

## 🛠️ Tech Stack

- **HTML5** — Single-file app
- **CSS3** — Custom dark-theme UI, animated progress bars, responsive grid
- **Vanilla JavaScript** — Full calculation engine, no frameworks or libraries

---

## 📄 License

MIT — free to use, modify, and distribute.
