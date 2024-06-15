# Aviation-Analysis
## Project Overview
This project involves an exploratory analysis of aviation accident data from the National Transportation Safety Board (NTSB). The goal is to determine the safest aircraft makes and models for investment and identify the most profitable business opportunities within the aviation industry. The analysis spans data from 1962 to 2023, covering various aspects such as accident details, aircraft information, injury severity, and more.

## Business Problem
Our company is expanding into the aviation industry to diversify its portfolio. We aim to purchase and operate aircraft for commercial and private enterprises. This project is focused on:
1. Determining if aviation is a viable investment.
2. Identifying the safest aircraft makes and models.
3. Pinpointing the most profitable business opportunities within the aviation industry.

## Data
The dataset includes civil aviation accidents and selected incidents in the United States and international waters. Key characteristics of the data include:
- Temporal coverage from 1962 to 2023
- Geographical scope including the United States and international waters
- Detailed event information (e.g., date, location, airport code)
- Aircraft specifics (e.g., make, model, engine type)
- Injury and damage data (e.g., total fatalities, serious injuries)
- Operational data (e.g., purpose of flight, weather conditions)
- Investigation details (e.g., investigation type, report status)

## Data Preparation
1. **Import Data**: Loaded the dataset into a DataFrame.
2. **Handle Missing Values**:
   - Filled categorical columns with mode or 'Unknown'.
   - Filled numerical columns with appropriate statistics (mean, median) or zeros.
3. **Data Type Conversion**: Ensured correct data types for each column.
4. **Remove Unnecessary Columns**: Dropped columns with excessive missing values or irrelevant information.
5. **Create New Features**: Derived new features such as the total number of injuries.
6. **Parameter Creation**: Created parameters for dynamic filtering in Tableau.
7. **Calculated Fields**: Developed calculated fields for filtering and analysis in Tableau.
8. **Export Cleaned Data**: Saved the cleaned DataFrame to a CSV file for use in Tableau.

## Data Analysis and Modeling
1. **Exploratory Data Analysis (EDA)**:
   - Visualized key metrics such as the number of accidents over time, geographical distribution, and injury severity.
   - Analyzed trends and patterns in aircraft make and model incidents.
   - Investigated the impact of weather conditions and phases of flight on accident rates.
2. **Risk Assessment**:
   - Calculated accident rates per aircraft make and model.
   - Assessed injury severity distribution across different aircraft types.
   - Identified high-risk conditions and phases of flight.
3. **Profitability Analysis**:
   - Evaluated the potential profitability of different aviation business segments.
   - Analyzed market demand and revenue potential for commercial vs. private aviation.
   - Identified key factors influencing profitability in the aviation industry.
4. **Dashboard Creation**:
   - Developed an interactive Tableau dashboard for dynamic analysis and visualization.
   - Included filters for Make, Model, and Location to enable detailed insights.
   - Created visualizations to highlight key findings and support decision-making.

## Results
1. **Investment Viability**:
   - The trend shows a decrease in aviation accidents over time, indicating improved safety and a viable investment.
2. **Low-Risk Aircraft**:
   - Certain aircraft makes and models exhibit lower accident rates and injury severities, making them suitable for purchase.
3. **Profitability Insights**:
   - Both commercial and private aviation sectors show significant revenue potential, with commercial aviation being slightly more profitable.
4. **Key Risk Factors**:
   - Adverse weather conditions and specific phases of flight were identified as high-risk factors.
5. **Geographical Distribution**:
   - Certain regions have higher accident frequencies, informing better strategic planning and risk management.

## Conclusion
This data-driven analysis equips our company with the insights needed to make informed decisions about aircraft purchases and market entry strategies. By focusing on safety, reliability, and profitability, we can confidently expand into the aviation industry and capitalize on new opportunities.

## How to Use
1. Clone the repository:
   ```bash
   git clone https://github.com/WafulaNasombi/Aviation-Analysis.git
