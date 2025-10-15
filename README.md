# F1 Technology Sponsorship Intelligence

Interactive infographic analyzing technology sponsor distribution across 10 Formula 1 teams with comprehensive visualizations.

![F1 Tech Sponsorship](https://img.shields.io/badge/Teams-10-orange?style=flat-square)
![Total Sponsors](https://img.shields.io/badge/Total%20Sponsors-302-blue?style=flat-square)
![Tech Sponsors](https://img.shields.io/badge/Tech%20Sponsors-86-green?style=flat-square)
![Version](https://img.shields.io/badge/version-1.0-red?style=flat-square)

## Overview

A comprehensive visual analysis of technology sponsorship penetration across Formula 1 teams, revealing which teams attract the most tech partners and which technology categories dominate F1 sponsorships.

**Live Demo:** Open `f1-tech-sponsorship-infographic.html` in any modern browser.

## Key Insights

- **Mercedes-AMG Petronas** leads with **44%** tech sponsor penetration
- **McLaren F1 Team** has the most comprehensive coverage with all **8 tech categories**
- **Data Analytics** and **Hardware & Networking** are the most common categories (**9 teams** each)
- Average tech sponsor penetration across F1: **29.4%**
- **86 technology sponsors** out of **302 total sponsors** analyzed

## Visualizations

The infographic includes **8 interactive Chart.js visualizations**:

### 1. Technology Sponsor Penetration Rate
Horizontal bar chart showing percentage of total sponsors in the technology category for each team.

### 2. Total Sponsor Portfolio Size
Horizontal bar chart displaying overall sponsor count per team, ranked by portfolio size.

### 3. Technology Sponsor Count by Team
Vertical bar chart showing absolute number of technology sponsors per team.

### 4. Portfolio Size vs Tech Penetration
Scatter plot revealing the relationship between total sponsors and tech percentage (bubble size = tech sponsor count).

### 5. Overall Tech vs Non-Tech Distribution
Donut chart showing aggregate breakdown of technology (86) vs non-technology (216) sponsors.

### 6. Sponsor Composition Breakdown
Stacked bar chart displaying tech (orange) vs non-tech (gray) sponsors for each team.

### 7. Team Technology Category Coverage
Horizontal stacked bar chart showing distribution of 8 tech categories for each team.

### 8. Technology Category Distribution
Donut chart displaying overall tech category penetration across all teams.

## Technology Categories

The analysis tracks **8 technology categories**:

1. **Data Analytics** - 9 teams
2. **Hardware & Networking** - 9 teams
3. **AI/ML** - 8 teams
4. **Cloud & HPC** - 7 teams
5. **Cybersecurity** - 7 teams
6. **Collaboration** - 6 teams
7. **ERP** - 3 teams
8. **Data Storage** - 3 teams

## Teams Analyzed

- McLaren F1 Team
- Mercedes-AMG Petronas F1 Team
- Visa Cash App Racing Bulls
- Atlassian Williams Racing
- Oracle Red Bull Racing
- Kick Sauber F1 Team
- MoneyGram Haas F1 Team
- Aston Martin Aramco F1 Team
- BWT Alpine F1 Team
- Scuderia Ferrari HP

## Features

- **Interactive Charts** - Hover over data points for detailed information
- **Responsive Design** - Works seamlessly on desktop and mobile devices
- **Clean Styling** - Midnight Flame design theme with warm beige/cream backgrounds
- **Data Labels** - All values visible directly on charts
- **Material Icons** - Professional icon system from Google Fonts
- **No Dependencies** - Single HTML file, works offline

## Tech Stack

- **HTML5, CSS3, JavaScript**
- **Chart.js** - Interactive chart library
- **chartjs-plugin-datalabels** - Data label plugin
- **JetBrains Mono** - Typography
- **Material Icons** - Icon system

## Usage

1. **Clone the repository:**
   ```bash
   git clone https://github.com/aref-vc/f1-tech-sponsorship-intelligence.git
   ```

2. **Open the infographic:**
   ```bash
   cd f1-tech-sponsorship-intelligence
   open f1-tech-sponsorship-infographic.html
   ```

   Or simply double-click `f1-tech-sponsorship-infographic.html` in your file browser.

3. **Explore the data:**
   - Hover over charts for detailed tooltips
   - View legend markers for category identification
   - Analyze patterns across different visualizations

## Data Source

Data sourced from `F1_Tech_Category.xlsx` containing:
- **Data Sheet**: Team-level sponsor counts and tech penetration percentages
- **Distribution Sheet**: Technology category coverage per team
- **Full List Sheet**: Complete sponsor listings with partnership categories

## Design System

### Color Palette

- **Background**: `#FFFCF2` (Warm Beige)
- **Cards**: `#FDF9ED` (Cream)
- **Accent**: `#EB5E28` (Orange)
- **Text Primary**: `#252422` (Dark)
- **Text Secondary**: `#403D39` (Charcoal)

### Typography

- **Font Family**: JetBrains Mono
- **Weights**: 300, 400, 500, 600, 700

## Project Structure

```
f1-tech-sponsorship-intelligence/
├── f1-tech-sponsorship-infographic.html  # Main infographic file
├── F1_Tech_Category.xlsx                  # Source data
└── README.md                              # Documentation
```

## Browser Support

- Chrome (recommended)
- Firefox
- Safari
- Edge
- Opera

## Contributing

This is a data visualization project. To contribute updates:

1. Fork the repository
2. Update data in `F1_Tech_Category.xlsx`
3. Modify visualization code in the HTML file
4. Submit a pull request

## License

This project is open source and available for educational and analytical purposes.

## Credits

**Data Analysis & Visualization:** Falcon HQ - 2025

**Powered by:** [Claude Code](https://claude.com/claude-code)

---

⭐ **Star this repo** if you find it useful!

📊 **View Live:** Simply open the HTML file in your browser

🏎️ **Formula 1** technology sponsorship intelligence at your fingertips
