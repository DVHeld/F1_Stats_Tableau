# F1 Stats: A Comprehensive Formula 1 Data Analysis Project

## 📋 Project Overview

F1 Stats is an interactive Tableau dashboard suite that provides comprehensive insights into Formula 1 racing data spanning from 1950 to 2024. This project transforms raw racing data into compelling visual narratives, exploring everything from circuit histories and race dynamics to mechanical reliability patterns across different regulatory eras.

The project consists of seven specialized dashboards, each focusing on different aspects of Formula 1 analytics, designed for racing enthusiasts, data analysts, and anyone interested in the technical and competitive evolution of motorsport's premier championship.

## 📊 Data Source

This project utilizes the **Formula 1 World Championship (1950-2024)** dataset from Kaggle:
- **Source**: [Formula 1 World Championship Dataset](https://www.kaggle.com/datasets/rohanrao/formula-1-world-championship-1950-2020)
- **Coverage**: 70+ years of Formula 1 data (1950-2024)
- **Scope**: Race results, lap times, circuit information, constructor data, driver statistics, and technical failure records

### Key Data Tables:
- **Races**: Race information including dates, circuits, and years
- **Results**: Race outcomes, positions, and status information  
- **Drivers**: Driver profiles and career information
- **Constructors**: Team/manufacturer data
- **Circuits**: Track locations and specifications
- **Lap_Times**: Detailed lap-by-lap position and timing data
- **Status**: Race completion status including mechanical failures

## 🏁 Dashboard Collection

### 1. Circuit Saga: Venues and Victories
*Exploring the iconic venues that have shaped Formula 1 history*

**Features:**
- **Circuit Statistics Table**: Comprehensive list of circuits with locations and race counts
- **Global Circuit Map**: Interactive world map showing circuit locations with color-coded race frequency
- **Race History Table**: Detailed race records with dates, circuits, and winners (drivers & constructors)
- **Year Range Filter**: "Between" slider to explore specific time periods

**Insights**: Discover which circuits have hosted the most races, explore the global expansion of F1, and trace the history of victories across different venues.

---

### 2. From Grid to Finish, a Rollercoaster of Fortunes: Position Changes at the [Race]
*Analyzing the dramatic position battles within individual races*

**Features:**
- **Race Selection Dropdown**: Choose any race from the dataset
- **Starting Grid Table**: Shows drivers and their qualifying positions
- **Dynamic Position Chart**: Line graph tracking each driver's position throughout the race
- **Constructor Color Coding**: Lines colored by team for easy identification
- **Driver Highlighter**: Interactive tool to focus on specific drivers
- **Constructor Legend**: Visual reference for team colors

**Insights**: Witness the drama of individual races unfold lap by lap, identify the most dramatic comeback drives, and analyze strategic position battles.

---

### 3. Mechanical Misfortune: Technical Failures Through the Years (Absolute)
*Examining the absolute frequency of technical failures over F1 history*

**Features:**
- **Annual Failure Trends**: Line graph showing total mechanical failures by year
- **Failure Type Analysis**: Paged line graphs breaking down specific failure categories
- **Failure Distribution**: Bar chart ranking failure types by frequency
- **Year Range Filter**: "Between" slider for temporal analysis
- **Constructor Filter**: Focus on specific teams
- **Engine Failure Toggle**: Option to exclude engine failures for clearer analysis

**Insights**: Track how mechanical reliability has evolved, identify the most problematic components, and compare failure patterns across different teams.

---

### 4. Mechanical Misfortune: Technical Failure Rates Through the Years (Rates)
*Analyzing normalized failure rates accounting for grid size variations*

**Features:**
- **Failure Rate Trends**: Line graph showing percentage of cars ending races due to mechanical issues
- **Rate by Failure Type**: Paged analysis of specific failure category rates
- **Proportional Failure Analysis**: Bar chart showing what percentage each failure type represents
- **Year Range Filter**: Temporal analysis controls
- **Constructor & Engine Failure Filters**: Customizable analysis scope

**Insights**: Understand true reliability improvements by normalizing for changing grid sizes, identify which failure types have become more or less common proportionally.

---

### 5. Mechanical Misfortune: Technical Failure Rates Through the Eras (Era)
*Exploring reliability patterns across major F1 technical regulation periods*

**Features:**
- **Era-Based Analysis**: Combined failure rates and absolute counts by regulatory period
- **Paged Era Comparison**: Failure type analysis across different technical eras
- **Era-Specific Failure Distribution**: Bar charts showing failure patterns per regulatory period
- **Technical Era Framework**: Based on major regulation changes (engine formulas, safety updates, etc.)
- **Constructor & Engine Failure Filters**: Customizable analysis parameters

**Technical Eras Covered:**
- Early Formula (1950-1960)
- 1.5L NA Era (1961-1965)
- 3.0L NA Era (1966-1985)
- Turbo Era (1986-1988)
- 3.5L NA Era (1989-1994)
- 3.0L V10 Era (1995-2005)
- 2.4L V8 Era (2006-2013)
- 1.6L V6 Hybrid Era (2014-2021)
- Ground Effect Era (2022+)

**Insights**: Understand how major technical regulation changes affected reliability, identify which eras were most/least reliable, and see how failure patterns evolved with technology.

---

### 6. The Breakdown Breakdown: Constructor Reliability Through the Years
*Comprehensive reliability comparison across teams and time periods*

**Features:**
- **Reliability Heat Map**: Matrix visualization with constructors (rows) vs. years (columns)
- **Color-Coded Reliability**: Green-red diverging color scheme indicating failure rates
- **Temporal Filtering**: Year range slider for focused analysis
- **Constructor Filter**: Select specific teams for comparison
- **Engine Failure Toggle**: Option to exclude engine failures

**Insights**: Quickly identify the most and least reliable constructors across different periods, spot reliability trends for specific teams, and discover which constructors dominated different eras.

---

### 7. Race Places by Year
*Seasonal championship battle visualization*

**Features:**
- **"Snakey" Line Visualization**: Multi-line chart showing all drivers' positions across a season
- **Race-by-Race Progression**: X-axis represents each race in chronological order
- **Position Tracking**: Y-axis shows finishing positions (1st, 2nd, 3rd, etc.)
- **Driver Performance Patterns**: Visualize consistency vs. volatility in driver performance

**Insights**: Analyze championship battles, identify the most consistent performers, and spot dramatic season-long narratives in driver performance.

## 🛠️ Technical Implementation

### Tools Used:
- **Tableau Public**: Primary visualization and dashboard creation platform
- **Data Modeling**: Established relationships between tables for optimal performance
- **Advanced Analytics**: Level of Detail (LOD) expressions, table calculations, and parameters

### Key Technical Features:
- **Interactive Filtering**: Cross-dashboard filter actions and parameter controls
- **Dynamic Calculations**: LOD expressions for complex aggregations across different granularities
- **Custom Groupings**: Regulatory era classifications and failure type categorizations
- **Performance Optimization**: Efficient data relationships and extract usage

## 🎯 Key Insights & Findings

- **Reliability Evolution**: Clear improvement in mechanical reliability over the decades
- **Engine Dominance**: Engine failures represent the largest category of mechanical issues
- **Era Patterns**: Each technical regulation era shows distinct reliability characteristics
- **Constructor Differences**: Significant reliability gaps between top-tier and developing teams
- **Geographic Trends**: Circuit analysis reveals the global expansion of Formula 1

## 🚀 Getting Started

### Prerequisites:
- Tableau Desktop or Tableau Public

### Installation:
1. Clone this repository
2. Open the Tableau workbook files (.twbx)

### Usage:
- Each dashboard is designed to be self-contained with intuitive controls
- Use filters and parameters to customize your analysis
- Hover over visualizations for detailed tooltips
- Export insights and visualizations as needed

## 📈 Future Enhancements

- **Predictive Analytics**: Machine learning models for reliability forecasting
- **Driver Analysis**: Expanded driver performance and career trajectory analysis
- **Weather Integration**: Impact of weather conditions on race outcomes and reliability

## 🤝 Contributing

Contributions are welcome! Please feel free to submit issues, suggestions, or pull requests to improve the analysis or add new insights.

## 📝 License

This project is open source and available under the [Unlicense](UNLICENSE).

## 🏎️ Acknowledgments

- **Kaggle** and **Vopani** for providing the comprehensive Formula 1 dataset
- **Formula 1** for decades of thrilling motorsport
- The **F1 community** for their passion and detailed record-keeping that makes this analysis possible

---

*"In Formula 1, data doesn't just tell the story of speed—it reveals the engineering battles, strategic decisions, and human drama that unfold at 300 km/h."*