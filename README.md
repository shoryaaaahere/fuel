Global Fuel Prices and Taxation TrendsA Comprehensive Global Performance Intelligence Report
Project Overview & ObjectivesEnergy pricing and fuel taxation play a pivotal role in macroeconomics, influencing inflation, transportation
costs, trade balances, and national fiscal policies. This project presents an end-to-end data analytics and visual intelligence solution 
analyzing global fuel price structures, taxation levels, and cross-national trend patterns.Key Objectives:Global Benchmarking: Evaluate how retail
prices for fuel (Gasoline and Diesel) vary across different income groups and geographical regions.Taxation Breakdown: Isolate the tax component 
within end-user fuel prices to identify nations with high subsidy regimes versus those leveraging fuel tax as a major source of state revenue.
Economic Correlation: Examine the relationship between fuel price volatility, national inflation rates, and GDP per capita.
Interactive Intelligence: Build a dynamic Tableau dashboard allowing policy analysts, researchers, and stakeholders to perform ad-hoc global 
and regional fuel price analyses.📊 Dataset DescriptionThe analysis is based on aggregated cross-country energy and macroeconomic datasets 
compiled from open data repositories (such as the World Bank, IMF, and GlobalPetrolPrices).Field NameData
TypeDescriptionCountry_CodeString (ISO-3)Three-letter country codeCountry_NameStringFull name of the countryRegionStringGeographical region 
classificationIncome_GroupStringWorld Bank income classification (High, Upper Middle, Lower Middle, Low)YearDate / IntegerObservation yearFuel_TypeStringType
of fuel (Gasoline, Diesel)Pump_Price_USDNumeric (Continuous)Retail price per liter in USDTax_Component_USDNumeric (Continuous)Estimated tax/duty component
per liter in USDSubsidy_FlagBoolean / StringIndicates whether fuel price is net-subsidizedGDP_per_CapitaNumeric (Continuous)Nominal GDP per capita (USD)🔍
Key Analysis AreasTax vs. Net Price Dissecting: Distinguishing baseline production/import prices from government levies and subsidies across major economies.
Regional Volatility & Disparity: Spatial mapping and variance metrics showing how geographic location impacts pump prices.Macroeconomic Drivers: 
Regression and correlation analysis comparing per capita income levels against fuel tax burdens.Subsidization Trends: Tracking countries operating below 
international crude baseline rates due to heavy state subsidies.🖥️ Tableau Dashboard FeaturesThe dynamic Tableau Public dashboard provides a multi-layered 
interactive experience:🌍 Interactive Global Heatmap: Visualizes fuel prices and tax percentages by country with hover tooltips detailing precise breakdowns.
🎛️ Dynamic Multi-Filtering: Filter seamless views by Fuel Type, Region, Income Bracket, and Year.
📈 Tax Component Decomposition Bar Charts: Comparative visual ranking of net fuel costs vs. applied tax levies.
💡 Executive KPI Cards: High-level summary metrics displaying global averages, highest/lowest price points, and maximum tax rates.
🔍 Drill-Down Country Profiles: Interactive detail pane allowing deep-dive comparisons between selected peer nations.
🛠️ Tools & Technologies UsedData Processing & Prep: Python (pandas, numpy),
Microsoft Excel / SQLData Visualization & BI: Tableau Desktop / Tableau PublicDocumentation & Version Control: Markdown,
Git, GitHub📁 Repository Structure├── data/
│   ├── raw_fuel_prices.csv        # Primary raw data file
│   └── cleaned_fuel_tax_data.csv  # Cleaned, standardized dataset used in Tableau
├── dashboard/
│   └── Global_Fuel_Prices_Report.twbx # Tableau Packaged Workbook
├── assets/
│   └── dashboard_preview.png      # Screenshot previews for presentation
├── README.md                      # Project documentation
└── LICENSE                        # Project license
🚀 How to Access the DashboardOption 1: View Online (Recommended)Access the fully interactive version hosted on Tableau Public:
👉 View Interactive Tableau Dashboard (Insert your Tableau link here)Option 2: Run Locally via Tableau Desktop / ReaderClone this repository:git clone https://github.com/your-username/global-fuel-prices-taxation.git
Navigate to the dashboard/ folder.Open Global_Fuel_Prices_Report.twbx using Tableau Desktop or Tableau Reader (Free).
