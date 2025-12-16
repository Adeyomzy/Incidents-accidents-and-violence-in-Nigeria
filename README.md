# Incidents, Accidents, and Violence in Nigeria

A comprehensive Power BI analytics project analyzing incident, accident, and violence data across Nigeria. This dashboard provides data-driven insights into safety trends, regional variations, and patterns to support informed decision-making and policy development.

## 📋 Project Overview

This project contains an interactive Power BI dashboard coupled with detailed data analysis of incidents, accidents, and violence occurrences throughout Nigeria. The analysis helps stakeholders understand:

- **Distribution patterns** of incidents across regions and time periods
- **Trend analysis** to identify emerging safety concerns
- **Regional variations** to highlight high-risk areas
- **Root cause patterns** to inform prevention strategies
- **Impact assessment** for evidence-based interventions

## 📁 Repository Structure

```
├── README.md                              # This file - comprehensive project documentation
├── Incidents rate in nigeria.pbix         # Main Power BI Dashboard file
├── Data/
│   └── Incident.xlsx                      # Source dataset with incident records
├── .git/                                  # Version control history
└── .gitattributes                         # Git configuration settings
```

### File Descriptions

#### `Incidents rate in nigeria.pbix`
The primary Power BI dashboard file containing:
- Interactive visualizations and charts
- Incident rate calculations and metrics
- Regional breakdown analysis
- Time-series trend analysis
- Drill-through capabilities for detailed investigation
- KPIs and summary statistics
- Filterable views by region, incident type, and time period

**Requirements to open:** Microsoft Power BI Desktop or Power BI Service access

#### `Data/Incident.xlsx`
The source dataset containing:
- Raw incident records with details on each occurrence
- Structured data in Excel format for easy import and refresh
- Key fields likely including: Date, Region, Incident Type, Severity, Location, and other relevant metrics
- Clean, tabular format ready for Power BI import
- Data source : https://www.kaggle.com/datasets/jogwums/incidents-accidents-and-violence-in-nigeria

## 🎯 Key Features

### Dashboard Capabilities
- **Interactive Filters** - Slice data by region, time period, and incident classification
- **Visual Analytics** - Charts, maps, and graphs for intuitive understanding
- **Drill-Through Analysis** - Navigate from summary metrics to detailed records
- **KPI Cards** - Quick overview of critical safety metrics
- **Time Series Trends** - Identify seasonal patterns and long-term trajectories
- **Regional Comparison** - Benchmark safety metrics across Nigeria's regions

### Data Insights
- Incident frequency distribution across geographical areas
- Temporal patterns and seasonal variations
- Incident type categorization and trends
- High-risk zones and periods requiring intervention
- Comparative analysis for resource allocation

## 🚀 Getting Started

### Prerequisites
- **Microsoft Power BI Desktop** (latest version) - [Download here](https://powerbi.microsoft.com/en-us/desktop/)
- Or **Power BI Service** online account access
- Excel compatibility for viewing the data source file

### Opening the Dashboard

1. **Download/Clone Repository**
   ```powershell
   git clone <repository-url>
   cd Incidents-accidents-and-violence-in-Nigeria
   ```

2. **Open Power BI File**
   - Launch Power BI Desktop
   - File → Open → Navigate to `Incidents rate in nigeria.pbix`
   - Select and open the file

3. **Refresh Data**
   - Once opened, click "Refresh" to load the latest data from `Incident.xlsx`
   - Wait for the data connection to establish

4. **Explore the Dashboard**
   - Use filters to segment data
   - Click visualizations to drill down
   - Export reports as needed

## 📊 Dashboard Metrics & KPIs

The Power BI dashboard includes key performance indicators such as:

| Metric | Purpose |
|--------|---------|
| Total Incidents | Overall count of recorded incidents |
| Incident Rate | Frequency per capita or per population unit |
| Regional Distribution | Geographic spread of incidents |
| Incident Type Breakdown | Categorization by nature of incident |
| Trending Analysis | Month-over-month or year-over-year growth |
| High-Risk Zones | Identification of concentration areas |
| Severity Metrics | Impact assessment and classification |

## 🔄 Data Refresh & Updates

### Updating with New Data
1. Open `Data/Incident.xlsx`
2. Add new incident records following the existing schema
3. Save the file
4. Open the Power BI file and click "Refresh" to reload data

### Data Maintenance
- Ensure data consistency and proper formatting
- Validate date fields are in recognized format
- Check for duplicate records before import
- Maintain regional naming conventions

## 🛠️ Technical Details

### Data Source
- **Format:** Excel Spreadsheet (xlsx)
- **Location:** `/Data/Incident.xlsx`
- **Connection Type:** Direct Excel import in Power BI

### Version Control
- Repository includes `.gitattributes` for proper file handling
- `.git` folder maintains project history and changes
- Git-based collaboration for team updates

## 📈 Use Cases

This dashboard is valuable for:

- **Policy Makers** - Evidence-based policy development and resource allocation
- **Law Enforcement** - Deployment planning and resource positioning
- **Community Organizers** - Identifying intervention areas
- **Researchers** - Pattern analysis and trend research
- **Government Agencies** - Safety reporting and public communication
- **NGOs** - Program planning and impact assessment

## 💡 Insights & Recommendations

### Typical Analyses
- Which regions show highest incident concentrations?
- Are incidents trending up or down over time?
- What types of incidents are most prevalent?
- Are there seasonal patterns to incidents?
- Which time periods and areas need most intervention?

## 🔒 Data Privacy & Usage

- Data should be handled according to Nigerian data protection guidelines
- Use for authorized purposes only
- Respect confidentiality of incident-related information
- Follow organizational data governance policies

## 🤝 Contributing

To contribute improvements or corrections:

1. Create a branch for your changes
2. Update data in `Data/Incident.xlsx` with proper documentation
3. Modify Power BI visualizations as needed
4. Test all filters and drill-through features
5. Commit with clear messages explaining changes
6. Submit pull request for review

## 📞 Support & Maintenance

- **Data Issues:** Check source file formatting in `Data/Incident.xlsx`
- **Connection Errors:** Verify file paths and ensure Excel is properly formatted
- **Dashboard Issues:** Update Power BI Desktop to latest version
- **Questions:** Refer to Power BI documentation or consult project stakeholders

## 📚 Additional Resources

- [Power BI Documentation](https://docs.microsoft.com/en-us/power-bi/)
- [Power BI Desktop Guide](https://docs.microsoft.com/en-us/power-bi/fundamentals/desktop-what-is-desktop)
- [Excel Data Best Practices](https://support.microsoft.com/en-us/office)
- [Data Analysis & Visualization Best Practices](https://powerbi.microsoft.com/en-us/blog/)

## 📄 License & Attribution

This project contains analysis of incidents, accidents, and violence in Nigeria for informational and decision-support purposes.

---

**Last Updated:** December 2025  
**Project Status:** Active  
**Maintained By:** Project Team

For questions or updates, please contact the project maintainers or submit an issue through the repository.
