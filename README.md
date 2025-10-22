# test-fixed-sec-app9

SEC Data Visualization for Apple Inc. (AAPL)

## Company Information
- **Name**: Apple Inc. (AAPL)
- **CIK**: 0000320193
- **Data Source**: SEC XBRL API

## Features
- Real-time SEC data visualization
- Interactive Chart.js charts
- Responsive data tables
- Support for ?CIK= query parameter
- Modern, mobile-responsive design

## Usage
1. Open `index.html` in a web browser
2. View the default company data (Apple Inc. (AAPL))
3. To view another company, add `?CIK=XXXXXXXXXX` to the URL

Example: `index.html?CIK=0000789019` (for Microsoft)

## Data Source
https://data.sec.gov/api/xbrl/companyconcept/CIK0000320193/dei/EntityCommonStockSharesOutstanding.json

## License
MIT License

## Technical Stack
- HTML5, CSS3, JavaScript (ES6+)
- Chart.js for visualizations
- SEC EDGAR API for data