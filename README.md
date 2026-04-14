# 🏏 India vs South Africa — ODI Analytics Dashboard

A Power BI dashboard analyzing the **complete all-time head-to-head ODI record** between India and South Africa across batting, bowling, and fielding disciplines. Data sourced directly from [ESPN Cricinfo's Statsguru](https://stats.espncricinfo.com).

---

## 📊 Dashboard Pages

| Page | Description |
|------|-------------|
| **Batting Data Analysis** | Per-player batting stats — matches, innings, runs, average, strike rate, balls faced, highest score, centuries, half-centuries, ducks, not-outs |
| **Bowling Data Analysis** | Per-player bowling stats — matches, innings, wickets, overs, average, economy, strike rate, 5-fers, 4-fers, maidens, best figures |
| **Fielding Data Analysis** | Per-player fielding stats — matches, innings, catches, dismissals, stumpings, catches as fielder, catches as WK, dismissals per innings, most dismissals in a match |

---

## 🗂️ Repository Structure

    ind-vs-sa-odi-dashboard/
    │
    ├── dashboard/
    │   └── IND_SA_ODI_HeadToHead_Dashboard.pbix
    │
    ├── screenshots/
    │   ├── Batting_Data.png
    │   ├── Bowling_Data.png
    │   └── Fielding_Data.png
    │
    ├── data/
    │   └── source_links.md
    │
    └── README.md

---

## 🔗 Data Source

Data extracted using **Power BI's built-in Web Connector** from ESPN Cricinfo's Statsguru — 9 pages consolidated across 3 stat types:

| Stat Type | Source URL |
|-----------|------------|
| Batting | `stats.espncricinfo.com → class=2, team=6, opposition=3, type=batting` |
| Bowling | `stats.espncricinfo.com → class=2, team=6, opposition=3, type=bowling` |
| Fielding | `stats.espncricinfo.com → class=2, team=6, opposition=3, type=fielding` |

- **Format:** ODI (`class=2`)
- **Team:** India (`team=6`)
- **Opposition:** South Africa (`opposition=3`)
- **Pages per stat type:** 3 (all pages included)

---

## 🛠️ Tools Used

| Tool | Purpose |
|------|---------|
| **Power BI Desktop** | Dashboard development & visualization |
| **Power BI Web Connector** | Extracting multi-page tabular data from ESPN Cricinfo |
| **Power Query** | Data consolidation and transformation |

---

## 📸 Dashboard Preview

### Batting Data Analysis
![Batting](screenshots/Batting_Data.png)

### Bowling Data Analysis
![Bowling](screenshots/Bowling_Data.png)

### Fielding Data Analysis
![Fielding](screenshots/Fielding_Data.png)

---

## ✨ Key Features

- **Player Slicer** — Select any player to instantly view their complete stat profile across their IND vs SA ODI career
- **Dynamic Career Span** — Automatically reflects the selected player's first and last match year
- **KPI Card Layout** — Clean, scannable stat cards for quick performance lookup
- **Custom Cricket Visuals** — Role-specific illustrations (batsman, bowler, wicket-keeper) for intuitive page navigation
- **All-time Historical Coverage** — Covers every IND vs SA ODI ever played

---

## 🚀 How to Use

1. Clone or download this repository
2. Open `dashboard/IND_SA_ODI_HeadToHead_Dashboard.pbix` in **Power BI Desktop**
3. Use the **Player** slicer (top right) to filter stats by any player
4. Navigate between **Batting**, **Bowling**, and **Fielding** pages using the tabs at the bottom

> **Note:** To refresh data, an active internet connection is required as data is pulled live from ESPN Cricinfo's Statsguru.

---

## 👤 Author

**Sambhav Gupta**
[GitHub](https://github.com/sambhavg18) • [LinkedIn](#)

---

## 📌 Part of

This project is part of my **Data Analytics Portfolio** — a collection of end-to-end analytics projects built using Excel, PostgreSQL, and Power BI.

> Check out my other project: [Quick Commerce Performance Dashboard](https://github.com/sambhavg18/quick-commerce-analytics)
