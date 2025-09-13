# SURE Trust SQL & Power BI Project Portfolio

SURE Trust SQL & Power BI portfolio: Python automation for Google Forms-MySQL integration, Power BI dashboards for bank loan risk analysis & fraud detection, enterprise customer complaints BI solution. Features real-time sync, advanced DAX, star schema modeling, KPI tracking & interactive visualizations.

## 📋 Table of Contents
- [Overview](#overview)
- [Projects](#projects)
- [Technologies Used](#technologies-used)
- [Installation & Setup](#installation--setup)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [Key Features](#key-features)
- [Screenshots](#screenshots)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

## 🎯 Overview

This repository contains a comprehensive project portfolio developed during the **SURE Trust SQL & Power BI Program** (May-August 2025). The portfolio demonstrates progressive skill development from backend automation to advanced business intelligence solutions, addressing real-world challenges in data integration, financial risk assessment, and customer service analytics.

**Program Details:**
- **Participant:** Gopika N G (BTech CSE Graduate)
- **Mentor:** Ms. Siddhika Shah (Software Engineer at HCLTech)
- **Organization:** SURE Trust
- **Duration:** May 2025 - August 2025

## 🚀 Projects

### 1. Google Forms to MySQL Integration
**Type:** Mini Project | **Domain:** Backend Automation

A robust Python-based system that automatically synchronizes Google Forms responses with MySQL databases in real-time.

**Key Features:**
- Real-time data synchronization
- Hash-based duplicate prevention
- Comprehensive error handling
- Automated scheduling with multiple execution modes
- Statistical reporting and monitoring

### 2. Bank Loan Application Analysis
**Type:** Mini Project | **Domain:** Financial Analytics

Interactive Power BI dashboard for analyzing loan applications, fraud detection, and risk assessment.

**Key Features:**
- CIBIL score impact analysis
- Fraud detection patterns
- Risk profiling by demographics
- Advanced DAX measures and KPIs
- Interactive drill-down capabilities

### 3. Consumer Complaints Dashboard
**Type:** Major Project | **Domain:** Customer Service Analytics

Enterprise-level Power BI solution with comprehensive complaint analysis and performance monitoring.

**Key Features:**
- Four interconnected dashboards
- Star schema data modeling
- KPI tracking and geographical mapping
- Advanced visualizations (treemaps, heatmaps)
- Executive reporting capabilities

## 🛠 Technologies Used

### Programming & Databases
- **Python 3.8+** - Backend automation and API integration
- **MySQL** - Database operations and data storage
- **JSON** - Configuration management

### Business Intelligence
- **Microsoft Power BI** - Dashboard development and visualization
- **DAX** - Advanced calculations and measures
- **Power Query** - Data cleaning and transformation

### APIs & Libraries
- **Google Sheets API** - Form data retrieval
- **Google Drive API** - Cloud service integration
- **Libraries:** mysql-connector-python, gspread, google-oauth2, pandas, schedule

### Development Tools
- **Visual Studio Code** - Development environment
- **Google Cloud Console** - API management
- **Git** - Version control

## 📦 Installation & Setup

### Prerequisites
- Python 3.8 or higher
- MySQL Server
- Power BI Desktop
- Google Cloud Console account
- Git

### Setup Instructions

1. **Clone the repository**
   ```bash
   git clone https://github.com/sure-trust/GOPIKA-N-G-g18-sql-and-power-bi.git
   cd GOPIKA-N-G-g18-sql-and-power-bi
   ```

2. **Install Python dependencies**
   ```bash
   pip install mysql-connector-python gspread google-auth pandas schedule
   ```

3. **Configure Google API credentials**
   - Create a service account in Google Cloud Console
   - Download credentials JSON file
   - Place in project directory and update config files

4. **Setup MySQL database**
   - Install MySQL Server
   - Create database and tables as per project requirements
   - Update database configuration in config files

5. **Configure Power BI**
   - Install Power BI Desktop
   - Open .pbix files from respective project folders
   - Update data source connections

## 🎮 Usage

### Google Forms Integration
```bash
# Full synchronization
python main.py --mode full_sync

# Sync only
python main.py --mode sync_only

# Scheduled execution
python main.py --mode schedule
```

### Power BI Dashboards
1. Open respective .pbix files in Power BI Desktop
2. Refresh data connections
3. Interact with dashboards using filters and drill-down features
4. Publish to Power BI Service for sharing

## 📁 Project Structure

```
├── Mini projects/
│   ├── Google-Forms-MySQL-Integration/
│   │   ├── src/
│   │   ├── config/
│   │   ├── logs/
│   │   └── README.md
│   └── Bank-Loan-Analysis/
│       ├── Bank_Loan_Analysis.pbix
│       ├── data/
│       └── README.md
├── Final capstone project/
│   ├── Consumer_Complaints_Dashboard.pbix
│   ├── data/
│   └── README.md
├── Documentation/
│   ├── Project_Reports/
│   └── Screenshots/
└── README.md
```

## ⭐ Key Features

### Technical Highlights
- **End-to-End Automation:** Complete data pipeline from form submission to database storage
- **Real-Time Processing:** Live data synchronization and monitoring
- **Error Resilience:** Comprehensive error handling and recovery mechanisms
- **Scalable Architecture:** Modular design supporting enterprise deployment

### Business Intelligence
- **Interactive Dashboards:** User-friendly interfaces with drill-down capabilities
- **Advanced Analytics:** Complex DAX measures and statistical analysis
- **Executive Reporting:** High-level KPIs and strategic insights
- **Multi-Dimensional Analysis:** Cross-functional data exploration

## 📸 Screenshots

### Google Forms Integration
![Data Flow Architecture](path/to/screenshot1.png)
![Processing Statistics](path/to/screenshot2.png)

### Bank Loan Analysis
![Risk Assessment Dashboard](path/to/screenshot3.png)
![Fraud Detection Analysis](path/to/screenshot4.png)

### Consumer Complaints Dashboard
![Overview Dashboard](path/to/screenshot5.png)
![Geographical Analysis](path/to/screenshot6.png)

## 🤝 Contributing

This project was developed as part of the SURE Trust educational program. While primarily for portfolio demonstration, suggestions and feedback are welcome.

### How to Contribute
1. Fork the repository
2. Create a feature branch (`git checkout -b feature/improvement`)
3. Commit changes (`git commit -am 'Add new feature'`)
4. Push to branch (`git push origin feature/improvement`)
5. Create a Pull Request

## 📜 License

This project is developed for educational purposes under the SURE Trust program. Please refer to individual project folders for specific licensing information.

## 📞 Contact

**Gopika N G**  
- **Program:** SURE Trust SQL & Power BI  
- **GitHub:** [sure-trust/GOPIKA-N-G-g18-sql-and-power-bi](https://github.com/sure-trust/GOPIKA-N-G-g18-sql-and-power-bi)
- **Mentor:** Ms. Siddhika Shah (Software Engineer, HCLTech)

**SURE Trust**  
- **Executive Director:** Prof. Radhakumari  
- **Website:** [SURE Trust Official](https://suretrust.org)

---

## 🙏 Acknowledgments

Special thanks to:
- **Ms. Siddhika Shah** for expert technical mentorship
- **Prof. Radhakumari** and **SURE Trust** for program organization
- **Open Source Community** for tools and resources

---

⭐ If you found this project helpful, please give it a star!

📈 **Portfolio Highlights:** Backend Automation | Business Intelligence | Data Analytics | Risk Assessment | Customer Insights
