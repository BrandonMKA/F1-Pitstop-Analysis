# 🏎️ Formula 1 Pit Stop Time Analysis (2011–2024)

This project explores Formula 1 pit stop performance using data visualization and analysis techniques. 
The goal is to identify which constructors consistently deliver the fastest pit stops, how pit stop
times have evolved over time, and how variability differs across drivers and teams.

The final product is an **interactive Tableau dashboard** that includes:
- Average pit stop time trends across seasons
- Box plot distribution of pit stop times by constructor
- Top 10 fastest pit stops overall
- Filtering by driver, constructor, and season

---

## 📊 Key Questions Explored
| Question | Insight Provided |
|----------|------------------|
| Which teams achieve the fastest pit stops? | Compare teams across seasons & individual events |
| How consistent is each constructor? | Box plots highlighting distribution and outliers |
| Who holds the fastest pit stops in modern F1? | Top 10 fastest stops analysis |
| How have pit strategies evolved over time? | Line trends showing improvement or decline |

---

## 🧠 Tools & Technologies
| Tool | Purpose |
|-------|---------|
| **Tableau Public** | Interactive dashboard & visual analytics |
| **Python (Pandas)** | Data cleaning + preprocessing |
| **Kaggle Dataset** | Raw pit stop performance data |

---

## 🗂️ Dataset
Source: Formula 1 Pit Stop Dataset (Kaggle — by Akash Rane, 2024)  
🔗 https://www.kaggle.com/datasets/akashrane2609/formula-1-pit-stop-dataset

Data includes:
- Season, round, circuit, driver, constructor
- Individual pit stop durations
- Aggregated stop counts and timing

Cleaning Steps:
- Converted string-encoded pit stop lists to long format
- Parsed individual stop durations from milliseconds to seconds
- Removed null and erroneous values
- Normalized formatting for Tableau ingestion

---

## 📈 Dashboard Preview & Link
### **Interactive Tableau Dashboard**
🔗 *(Add your Tableau Public link here once published)*

### Example Views:
- Pit Stop Trend Over Time
- Distribution of Pit Stop Times by Constructor
- Top Fastest Pit Stops
- Scatter: Average vs. Total Stops

---

## 📁 Repository Structure
F1-Pitstop-Analysis/
│
├── README.md
├── data/
│ └── f1_pitstops_clean_long.csv
├── tableau/
│ └── F1_Pitstop_Analysis.twbx
├── notebooks/
│ └── data_cleaning.ipynb
└── images/
└── dashboard_preview.png

---

## 🔮 Future Improvements
- Add predictive modeling for pit stop strategy optimization
- Driver-level consistency KPIs
- Team color branding & animations
- Integrate real-time 2025 race update feeds

---

## 👤 Author
**Brandon Aulac**  
Data Analyst / Engineering Student  
UConn — School of Engineering   
