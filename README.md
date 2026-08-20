# My Apps & Websites

Welcome! This repository showcases my privacy-focused nutrition and performance analytics tools.

## Language

- **English (default):** this page
- **Deutsch:** [apps-websites.de.md](./apps-websites.de.md)

---

## Public Apps Overview

| App | Live URL | Purpose |
|-----|----------|---------|
| **Fuel Lens** | https://fuellens.vercel.app/?view=dashboard | Privacy-first nutrition analytics workspace for understanding dietary patterns, trends, and biometrics |
| **Fuel Calc** | https://fuelcalc-glucosefructos-ratio-calulator.lovable.app/ | Glucose:Fructose ratio calculator for endurance sports fueling optimization |

---

## Fuel Lens

**Privacy-focused nutrition and health-analysis website**

### Core Concept

Turn exported food, exercise, weight, and biometric data into understandable dashboards, trends, comparisons, goals, and reports — all processed locally in your browser.

> Help users understand how their food intake, nutrient balance, activity, body measurements, and energy expenditure relate over time.

### Key Features

#### 📥 Data Import
- **Supported sources:** Cronometer, FatSecret, FatSecret API, MyFitnessPal
- **Formats:** CSV, XLSX/XLS, PDF diary reports
- **Features:** Drag-and-drop files/folders, automatic recognition, password-protected workbooks
- **Data types:** Daily nutrition summaries, individual food servings, exercise sessions, weight/biometrics, meals

#### 📊 Dashboard
Quick overview of:
- Calories consumed, energy balance, calorie gap
- Exercise calories and estimated expenditure
- Protein, carbohydrate, and fat progress
- Nutrient goal achievement and ratios
- Adaptive TDEE context
- Top food contributors

#### 📅 Daily Diary
Focus on one selected day:
- Foods and servings with nutrient totals
- Energy intake and exercise
- Weight and biometric readings
- Progress against nutrient targets
- Both nutrient-focused and food-focused views

#### 📈 Nutrient Trends
Track almost any nutrient over time:
- Daily, weekly, four-week, quarterly, semester, and yearly views
- Average reference lines
- Goal and DRI context
- Searchable nutrient selection
- Date navigation and range controls

#### 📉 Biometric Trends
Chart measurements such as:
- Weight, body fat, body measurements
- Heart rate, resting heart rate, HRV
- Sleep-related metrics
- Imported biometric series
- Compare trends with goals

#### 🔥 Adaptive TDEE Analysis
Estimate Total Daily Energy Expenditure by comparing:
- Logged calorie intake
- Weight changes and smoothed trends
- Body composition
- Exercise information

Supports:
- First Principles TDEE
- Statistical TDEE
- BMR-based fallback calculations
- Activity-level assumptions
- Confidence and data-coverage indicators

*Intended as a planning estimate, not a medical assessment.*

#### 🎯 Goal Management
Configure:
- Daily calorie targets
- Protein, carbohydrate, fat targets
- Micronutrient minimums and maximums
- Nutrient ratios and visibility
- Target-band margins

Macro targets based on:
- Percentage ratios
- Fixed gram values
- Keto calculations
- Lean body mass and composition
- Exercise-based carbohydrate bonuses

#### 📐 Nutrient Ratios
Track relationships such as:
- Omega-6 / Omega-3
- Zinc / Copper
- Potassium / Sodium
- Calcium / Magnesium
- Calcium / Oxalate
- Fat as percentage of calories
- Custom nutrient ratios

#### 🔍 Food Browser & Comparison
- Search and browse imported foods
- Inspect nutrient details within date ranges
- Compare foods side by side
- Per 100g or per 100 calories
- Rankings, medals, category scores
- Data coverage indicators

#### 🏅 Nutrient-Density Scoring
Multiple scoring systems:
- Custom Exponential Model
- NRF 9, 15, 21, 26 variants

Considers:
- Positive nutrients
- Nutrients to limit
- Category weighting
- Missing-data coverage
- Diminishing returns

#### 🏥 Medical Report Builder
Create structured reports for healthcare discussions:
- Dashboard summary
- Energy, macros, micronutrients
- Meals and diary
- Biometrics and charts
- Configurable sections, date ranges, aggregation
- Export/print as PDF

*Designed to support medical conversations, not diagnose conditions.*

#### 🤖 AI Context Export
Create compact CSV containing:
- Selected nutrients, calories, exercise
- Weight, body fat, sleep, heart-rate metrics
- Daily or weekly aggregation
- Previewed output for review

*Review before sharing — may contain sensitive health information.*

#### 🔒 Data Storage & Privacy
Client-side processing model:
- Save data in browser
- Load saved sessions
- Export/import full backups
- Clear stored data and settings
- **Health data stays in the browser during normal use**
- Calculations and charts run locally
- No backend transmission required for production analysis

*Treat backup files, medical reports, and AI exports as sensitive personal-health files.*

#### 📚 Built-in Documentation
Wiki explains:
- Uploading data
- Dashboard and diary usage
- Goals and trends
- Adaptive TDEE
- Food comparison
- Medical reports
- AI context export
- Data management and privacy
- Nutrient scoring models

### Intended Workflow

1. Export nutrition/health data from supported app
2. Upload files or connect FatSecret
3. Review imported data
4. Configure goals (calories, macros, nutrients, ratios, scoring)
5. Use dashboard for quick overview
6. Investigate trends, foods, biometrics, TDEE
7. Compare foods or generate reports
8. Export backup, medical report, or AI-analysis dataset when needed

**In short:** Fuel Lens is a personal nutrition analytics workspace — private, data-driven, customizable, and useful for long-term dietary and health-pattern review.

---

## Fuel Calc

**Glucose:Fructose Ratio Calculator for Endurance Fueling**

### Core Concept

Enter internal sugar values (glucose, fructose, sucrose, starch) from Cronometer to find optimal fueling ratios for cycling, running, and triathlon.

### How It Works

1. **Input sugars:** Glucose, fructose, sucrose, starch, maltose, lactose, galactose, allulose
2. **Choose preset:** 1:0.80, 1:1, or 2:1 ratio
3. **Get action plan:** Calculator tells you how much glucose or fructose to add
4. **Optimize strategy:** Adds glucose or fructose to reach target while keeping existing amounts

### Using with Cronometer

1. Open Cronometer diary → **Trends** tab
2. Enable **Glucose**, **Fructose**, **Sucrose**, **Starch** in nutrient report
3. Copy gram values for meal/day/training window
4. Paste into calculator and pick preset
5. Follow action plan to add or swap sugars until you hit target ratio

### Sugar Types Explained

| Sugar | Description | Contribution |
|-------|-------------|--------------|
| **Glucose** | Simplest form, absorbed via SGLT1. Primary fuel for muscles/brain during exercise. | 100% glucose side |
| **Fructose** | Fruit sugar via GLUT5 transporter. Runs independently, increases total carb oxidation. | 100% fructose side |
| **Sucrose** | Table sugar: 1 glucose + 1 fructose bonded together. | Split: 0.5g glucose + 0.5g fructose |
| **Starch** | Complex carb (long glucose chains). Digestion breaks down to glucose. | 100% glucose side |
| **Maltose** | Two glucose units linked. Rapidly broken down to glucose. | 100% glucose side |
| **Lactose** | Milk sugar: glucose + galactose. Galactose uses SGLT1. | 100% glucose side |
| **Galactose** | Single sugar in dairy/plants. Uses SGLT1 transporter. | 100% glucose side |
| **Allulose** | Rare, low-calorie sugar not metabolized for energy. | Excluded from ratio |

### Science Background

The glucose-to-fructose ratio is crucial for intestinal absorption:

- **SGLT1 transporters** move glucose, saturate at ~60–90 g/h
- **Adding fructose** activates GLUT5 transporter (runs in parallel)
- **Total carb oxidation** can reach 90–120 g/h
- **1:0.8 ratio** (current research) reduces GI distress vs older 2:1 standard while maximizing fuel availability

### Features

- **Real-time ratio calculation** with current vs target comparison
- **Action plan** with precise recommendations
- **Optimization strategy** that preserves existing intake
- **OCR support:** Upload or paste nutrition screenshots (Ctrl/Cmd+V) for automatic value extraction
  - 100% on-device processing (free forever, no image upload)
  - First scan downloads OCR engine once
- **Works with any nutrition tracker** that provides sugar breakdown
- **Handles edge cases** when glucose or fructose is zero

---

## Technology & Privacy

Both apps share core principles:

✅ **Client-side processing** — your data stays in your browser  
✅ **No backend required** for normal analysis  
✅ **Privacy-first** — calculations run locally  
✅ **Free forever** — no subscriptions or data monetization  
✅ **Open access** — browser-based, no installation needed

---

## FAQ

**Can I use Fuel Calc with apps other than Cronometer?**  
Yes. Any tracker or nutrition label listing glucose, fructose, sucrose, and starch will work.

**What if glucose or fructose is zero?**  
The ratio collapses to the available sugar only. The action plan recommends adding the missing sugar to reach target.

**Does Fuel Lens send my data anywhere?**  
No. All processing happens in your browser. Data only leaves if you explicitly export a backup, report, or AI context file.

**Can I delete my data?**  
Yes. Fuel Lens includes clear stored data and settings options.

**Is this medical advice?**  
No. Both tools are for personal analysis and planning. Consult healthcare professionals for medical decisions.

---

## Links

- **Fuel Lens:** https://fuellens.vercel.app/?view=dashboard
- **Fuel Calc:** https://fuelcalc-glucosefructos-ratio-calulator.lovable.app/

---

*Last updated: 2026-08-20*


