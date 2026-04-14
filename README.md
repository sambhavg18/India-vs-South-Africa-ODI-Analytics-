# India vs South Africa — ODI Analytics Dashboard

A Power BI dashboard analyzing the **complete all-time head-to-head ODI record** between India and South Africa across batting, bowling, and fielding disciplines. Data sourced directly from ESPN Cricinfo's Statsguru

---

## 📊 Dashboard Pages

| Page | Description |
|------|-------------|
| **Batting Data Analysis** | Player batting stats — matches, innings, runs, average, strike rate, balls faced, highest score, centuries, half-centuries, ducks, not-outs |
| **Bowling Data Analysis** | Player bowling stats — matches, innings, wickets, overs, average, economy, strike rate, 5-fers, 4-fers, maidens, best figures |
| **Fielding Data Analysis** | Player fielding stats — matches, innings, catches, dismissals, stumpings, catches as fielder, catches as WK, dismissals per innings, most dismissals in a match |

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

## 🛠️ Tools Used

| Tool | Purpose |
|------|---------|
| **Power BI Desktop** | Dashboard development & visualization |
| **Power BI Web Connector** | Extracting multi-page tabular data from ESPN Cricinfo |
| **Power Query** | Data consolidation and transformation |

## Why Web Connector?

Most cricket analytics projects rely on manually downloaded CSV files. However, this dashboard is connected directly to ESPN Cricinfo's Statsguru via Power BI's Web Connector, so hitting refresh automatically pulls the latest data with no manual work. All 9 pages across batting, bowling, and fielding are consolidated in one go, and replicating this for any other bilateral series is as simple as changing the team values in the URL. This makes the dashboard a **live analytics tool** rather than a static report.

---

