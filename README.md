# Temporal Inflow Anomaly Tracker Dashboard

A professional government-style analytics dashboard designed to help officials identify unusual Aadhaar enrollment spikes in Assam border PIN codes before policy deadlines.

## Features

### Core Analytics
- **Dashboard Overview**: Summary cards showing total PINs, high-risk PINs, and latest anomaly month
- **PIN-wise Risk Heatmap**: Color-coded visualization (green/yellow/red) for risk levels
- **Time-series Analysis**: Line charts with policy date markers

### Advanced Features
1. **Anomaly Detection**: Statistical analysis to identify unusual enrollment patterns
2. **Predictive Analytics**: Forecast future enrollment trends
3. **Geographic Mapping**: Interactive Leaflet.js map showing PIN locations with risk indicators
4. **Age Analysis**: Demographic breakdown of enrollments by age groups
5. **Pattern Recognition**: Identify clusters and patterns in enrollment data
6. **Comparative Analysis**: Compare multiple PINs side-by-side
7. **Alert System**: Configurable alerts for threshold breaches
8. **Data Quality Assessment**: Evaluate completeness and reliability of data
9. **Correlation Analysis**: Discover relationships between variables
10. **Report Generator**: Export customizable reports in multiple formats

### Interactive Features
- Live search functionality
- Real-time notifications
- Smooth animations and transitions
- Keyboard shortcuts for quick navigation
- Responsive design for all devices

## Technology Stack

- **Frontend**: HTML5, CSS3, JavaScript (Vanilla)
- **Mapping**: Leaflet.js
- **Design**: Modern light theme with professional government aesthetics
- **Data Format**: CSV with flexible column parsing

## CSV Data Format

The dashboard accepts CSV files with the following columns:

- **Date**: DD-MM-YYYY format
- **State**: State name
- **District**: District name
- **Pincode**: 6-digit PIN code
- **Age 0 5**: Enrollment count for age 0-5
- **Age 5 17**: Enrollment count for age 5-17
- **Age 18 Greater**: Enrollment count for age 18+

## Installation

1. Clone this repository:
```bash
git clone https://github.com/yourusername/temporal-inflow-anomaly-tracker.git
```

2. Open `index.html` in a modern web browser

No build process or dependencies required!

## Usage

1. **Upload Data**: Click "Choose CSV File" and select your Aadhaar enrollment data
2. **Navigate**: Use the sidebar to access different analysis views
3. **Analyze**: Explore various features like anomaly detection, predictions, and geographic mapping
4. **Export**: Generate reports for policy decisions

## Features Overview

### Dashboard
- Real-time summary statistics
- Risk level indicators
- Quick access to critical metrics

### PIN Analysis
- Detailed view of individual PIN codes
- Monthly enrollment trends
- Risk assessment with explanations

### Anomaly Detection
- Statistical outlier identification
- Configurable sensitivity levels
- Detailed anomaly reports

### Geographic Map
- Interactive Leaflet map
- Color-coded risk markers
- Assam-Bangladesh border visualization

### Predictive Analytics
- Future enrollment forecasts
- Trend analysis
- Growth rate predictions

### Data Export
- Filtered CSV export
- NRC-ready format
- Customizable data selection

## Design Philosophy

- **Professional**: Clean, government-appropriate styling
- **Minimal**: No clutter, focused on data
- **Formal**: Trustworthy and authoritative
- **Accessible**: Clear typography and high contrast
- **Responsive**: Works on desktop, tablet, and mobile

## Browser Support

- Chrome (recommended)
- Firefox
- Edge
- Safari

## License

This project is created for government policy analysis purposes.

## Disclaimer

This dashboard provides aggregated data analysis only. All data should be verified through official channels before making policy decisions.

## Contributing

Contributions are welcome! Please feel free to submit issues or pull requests.

## Contact

For questions or support, please open an issue on GitHub.
