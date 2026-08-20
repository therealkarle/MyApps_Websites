# My Apps & Websites

Welcome! This repository showcases my privacy-focused nutrition and performance analytics tools.

## Language

- **English (default):** this page
- **Deutsch:** [apps-websites.de.md](./apps-websites.de.md)

---

## Public Apps Overview

| App | Live URL | Purpose |
|-----|----------|---------|
| **[Fuel Lens](#fuel-lens)** | https://fuellens.vercel.app/?view=dashboard | Nutrition analytics workspace for understanding dietary patterns, trends, and biometrics |
| **[Fuel Calc](#fuel-calc)** | https://fuelcalc-glucosefructos-ratio-calulator.lovable.app/ | Glucose:Fructose ratio calculator for endurance sports fueling optimization |

---

## GitHub Repositories

| Repository | GitHub URL | Description |
|------------|------------|-------------|
| **[TourTimeCalulator](#tourtlocalulator)** | https://github.com/therealkarle/TourTimeCalulator | Tour time predictions with Strava API integration |
| **[SleepTempFinder](#sleeptempfinder)** | https://github.com/therealkarle/SleepTempFinder | Sleep environment correlation analysis using R |
| **[RuterfahrenIn_BatchDateien](#ruterfahrenin_batchdateien)** | https://github.com/therealkarle/RuterfahrenIn_BatchDateien | Windows batch scripts for scheduled PC shutdown |
| **[ActivityWatch_StartUpScripts_FlorianZahl_launcher](#activitywatch_startupscripts_florianzahl_launcher)** | https://github.com/therealkarle/ActivityWatch_StartUpScripts_FlorianZahl_launcher | ActivityWatch startup orchestrator |
| **[ActivityWatch_Android-Import](#activitywatch_android-import)** | https://github.com/therealkarle/ActivityWatch_Android-Import | Google Drive to ActivityWatch sync for Android |
| **[ActivityWatch_iPad_Simple_Screentime_import](#activitywatch_ipad_simple_screentime_import)** | https://github.com/therealkarle/ActivityWatch_iPad_Simple_Screentime_import | iPad Screen Time to ActivityWatch import |
| **[ActivityWatch_email_summary](#activitywatch_email_summary)** | https://github.com/therealkarle/ActivityWatch_email_summary | Email reports from ActivityWatch data |
| **[ActivityWatch_iPad_sync_import](#activitywatch_ipad_sync_import)** | https://github.com/therealkarle/ActivityWatch_iPad_sync_import | iPad to PC ActivityWatch data sync |
| **[YT-DLP-GUI](#yt-dlp-gui)** | https://github.com/therealkarle/YT-DLP-GUI | GUI front-end for yt-dlp video downloader |
| **[PolarstepsPDFCreator](#polarstepspdfcreator)** | https://github.com/therealkarle/PolarstepsPDFCreator | PDF travel documentation from Polarsteps trips |
| **[InternalWindMachine](#internalwindmachine)** | https://github.com/therealkarle/InternalWindMachine | SimRacing telemetry-based PC fan controller |

---

## [Fuel Lens](https://fuellens.vercel.app/?view=dashboard)

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
Comprehensive [Wiki](https://fuellens.vercel.app/wiki) with guides for every feature, concept, and workflow in Fuel Lens — from first import to advanced analytics.

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

## [Fuel Calc](https://fuelcalc-glucosefructos-ratio-calulator.lovable.app/)

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
✅ **Privacy-first** — calculations run locally  
✅ **Open access** — browser-based, no installation or registration needed

---

## GitHub Repository Details

### [TourTimeCalulator](https://github.com/therealkarle/TourTimeCalulator)

Python-based tour time calculator with Strava API integration. Predicts tour completion times and synchronizes activities with your Strava account.

**Key Features:**
- Strava activity synchronization
- Tour time predictions and calculations
- Cross-platform support (Windows, macOS, Linux)

**Technology:** Python 3.11+

---

### [SleepTempFinder](https://github.com/therealkarle/SleepTempFinder)

Analyzes correlations between sleeping room temperature and humidity with sleep quality metrics. Helps identify optimal sleep conditions.

**Key Features:**
- Sleep score correlation analysis
- Resting heart rate (RHR) tracking
- Heart rate variability (HRV) analysis

**Technology:** R language

---

### [RuterfahrenIn_BatchDateien](https://github.com/therealkarle/RuterfahrenIn_BatchDateien)

Windows batch scripts for scheduled PC shutdown or hibernate. Automates power management after a specified duration.

**Key Features:**
- Scheduled shutdown/hibernate timers
- Windows batch automation
- Simple configuration

**Technology:** Batchfile (Windows)

---

### [ActivityWatch_StartUpScripts_FlorianZahl_launcher](https://github.com/therealkarle/ActivityWatch_StartUpScripts_FlorianZahl_launcher)

Launches ActivityWatch import scripts at Windows login in configurable stages. Manages startup sequence for ActivityWatch data collection.

**Key Features:**
- Configurable startup sequence
- Multi-stage launching
- Windows login integration

**Technology:** PowerShell

---

### [ActivityWatch_Android-Import](https://github.com/therealkarle/ActivityWatch_Android-Import)

Imports ActivityWatch exports from Google Drive and syncs to local instance. Bridges Android data with ActivityWatch ecosystem.

**Key Features:**
- Google Drive sync integration
- Incremental import support
- Window bucket mirroring to AFK buckets
- Automatic Android-to-PC data migration

**Technology:** Python, Google Drive API, ActivityWatch API

---

### [ActivityWatch_iPad_Simple_Screentime_import](https://github.com/therealkarle/ActivityWatch_iPad_Simple_Screentime_import)

Imports iPad Screen Time data from iCloud Drive into ActivityWatch. Tracks device usage patterns over time.

**Key Features:**
- iCloud Screen Time log parsing
- ActivityWatch event upload
- Device usage tracking

**Technology:** Python

---

### [ActivityWatch_email_summary](https://github.com/therealkarle/ActivityWatch_email_summary)

Generates and emails ActivityWatch summary reports. Provides automated productivity and sleep insights via email.

**Key Features:**
- Automated report generation
- Email delivery
- Productivity and sleep summaries

**Technology:** Python, SMTP

---

### [ActivityWatch_iPad_sync_import](https://github.com/therealkarle/ActivityWatch_iPad_sync_import)

Syncs iPad ActivityWatch data to local instance with status tracking. Maintains data consistency across devices.

**Key Features:**
- Incremental sync
- Backup intervals
- Sync status tracking

**Technology:** Python

---

### [YT-DLP-GUI](https://github.com/therealkarle/YT-DLP-GUI)

Graphical user interface for yt-dlp video downloader. Simplifies downloading videos and playlists from various platforms.

**Key Features:**
- User-friendly GUI interface
- Video downloading with yt-dlp
- Playlist support
- Error handling

**Technology:** Python, yt-dlp

---

### [PolarstepsPDFCreator](https://github.com/therealkarle/PolarstepsPDFCreator)

Generates PDF documents from Polarsteps trips with statistics and maps. Creates professional travel documentation.

**Key Features:**
- Overview map with route and step markers
- Individual step location maps (ESRI World Imagery)
- Adaptive photo grids (1-6 photos per step)
- Weather information per step
- Full travel journal formatting
- Tkinter GUI with sortable table

**Technology:** Python, Tkinter, tkcalendar

---

### [InternalWindMachine](https://github.com/therealkarle/InternalWindMachine)

PC fan controller using live telemetry data for SimRacing. Controls fans based on real-time racing metrics without extra hardware.

**Key Features:**
- Controls standard PC fans via motherboard headers
- No Arduino or extra hardware required
- Real-time telemetry integration

**Technology:** SimRacing telemetry, PC hardware control

---

## FAQ

**Can I use Fuel Calc with apps other than Cronometer?**  
Yes. Any tracker or nutrition label listing glucose, fructose, sucrose, and starch will work.

**What if glucose or fructose is zero?**  
The ratio collapses to the available sugar only. The action plan recommends adding the missing sugar to reach target.

**Does Fuel Lens send my data anywhere?**  
No. All processing happens in your browser. Data only leaves if you explicitly export a backup, report, or AI context file.

---

*Last updated: 2026-08-20*


