# Brandon Albers - Data, Business, and Operations Analyst Portfolio

## About Me
Experienced Operations Analyst specializing in data analytics, process optimization, and cost-saving strategies. Skilled in SQL, Python, Power BI, and advanced Excel, with a strong background in project management and team leadership. This portfolio showcases my work and demonstrates my expertise in leveraging data to drive business decisions and operational efficiencies.

## Table of Contents
- [Project 1: Landed Margin Forecasting Tool](landed_margin_forecasting_tool_index.html)
- [Project 2: Company vs 3rd Party Freight Model](company_vs_3rd_party_freight_model_index.html)
- [Project 3: Cost Optimization for Installation Operations](cost_optimization_for_installation_operations_index.html)
- [Additional Projects](#additional-projects)
- [Skills & Tools](#skills-tools)

## Confidentiality Notice:
**Confidentiality Notice:** This document and the information contained herein are confidential and proprietary. All company-specific details have been removed and replaced with randomized data for portfolio purposes.

## Project 1: Landed Margin Forecasting Tool

**Description:**  
The Freight Margin Forecasting Calculator is a strategic tool for management to evaluate the impact of varying bid margins on the landed margin. Due to a rule limiting the freight charge to a maximum of 20% of the customer’s product order total, standard high-margin bids (such as 70%) often result in reaching this cap, thus reducing the effective landed margin. By allowing users to adjust the bid margin, the calculator shows the achievable landed margin under these constraints. This tool enables management to make informed decisions by forecasting the effect of lowering the bid margin, optimizing profitability within regulatory pricing limits.

**Key Insights:**
- **Optimizes Profitability Within Pricing Constraints**
  - The tool helps management identify optimal margin settings that maximize profitability while staying within the 20% freight charge cap, ensuring compliance with pricing constraints.
- **Informed Decision-Making**
  - By forecasting the effect of different margin levels, the tool supports more informed and strategic decision-making, empowering management to adjust pricing based on detailed margin analysis.
- **Addresses Margin Limitations Impact**
  - The calculator directly addresses the impact of the 20% freight margin cap, showing how high-margin bids (like 70%) might reduce effective landed margins and offering alternatives for better profitability.
- **Identifies Cost-Effective Thresholds**
  - The tool identifies cost-effective thresholds for margin settings, helping management adjust pricing for the highest possible landed margin while complying with internal pricing policies.

**Skills and Tools Used:**
- **Excel Data Analysis**
  - Utilized Excel to process and analyze large sets of historical order data to calculate margin adjustments and determine their impact on landed margins.
- **Linear Functions and Regression Analysis**
  - Employed linear functions to model the relationship between margin adjustments and landed margin outcomes, providing accurate forecasts for different margin scenarios.
- **Data Management and Historical Analysis**
  - Managed and organized historical order data, enabling efficient analysis of past sales trends to predict future margin behaviors under various pricing rules.
- **Revenue and Cost Calculations**
  - Calculated revenue and associated costs by incorporating freight limits, ensuring the forecast accurately reflects potential revenue under specific margin conditions.
- **Pivot Tables and Data Visualization**
  - Created pivot tables to summarize key data points, and applied data visualization techniques (such as charts and graphs) to present margin adjustments and their impacts in a clear, actionable format.
- **Categorization and Conditional Formatting**
  - Used categorization to group orders based on their margin performance and applied conditional formatting to highlight key thresholds and exceptions that impact overall margin performance.
- **Data Validation and Forecast Modeling**
  - Implemented data validation techniques to ensure input accuracy and applied forecasting models to predict the impact of different margin adjustments on profitability.

[View Project](Data-Driven-Insights-Business-Operations-Analysis-Portfolio/landed_margin_forecasting_tool)

## Project 2: Company vs. 3rd Party Freight Model

**Description:**  
The Company vs. 3rd Party Freight Model evaluates the potential cost savings of hiring in-house drivers compared to relying solely on third-party carriers. Using a combination of internal order data and public datasets, this analysis estimates the per-mile cost for company-managed freight by factoring in additional expenses for in-house drivers, such as wages, benefits, fuel, and lodging. 

To support this analysis, Brandon accessed a massive dataset from the Bureau of Economic Research, containing 30+ billion rows of distance data between U.S. zip codes. He developed a custom script to filter this data to include only the relevant zip code (55060), enabling him to calculate delivery distances and compare per-mile costs charged by third-party carriers in various states. Factoring in costs unique to operating in-house, such as vehicle maintenance, fuel consumption, and driver lodging, the model projected annual savings of approximately $239,000, with potential savings exceeding $500,000 when accounting for variable factors.

**Key Insights:**
- **Significant Annual Savings Potential**
  - The analysis revealed a potential annual savings of $239,000 by hiring in-house drivers, with additional variable factors suggesting total savings could exceed $500,000.
- **Cost per Mile Comparison**
  - Comparing per-mile costs for in-house drivers versus third-party carriers showed that managing freight internally could reduce expenses, especially with state-specific cost variations.
- **Value of External Data Integration**
  - External data, such as zip code distances from the Bureau of Economic Research, provided essential insights, proving that strategic data integration can reveal cost-saving opportunities.
- **Unquantified Savings Potential**
  - Additional potential savings from route optimization and improved scheduling control were identified, suggesting further cost benefits beyond the primary calculations.
- **Long-Term Strategic Impact**
  - Hiring in-house drivers could reduce reliance on third-party carriers, offering more control over delivery costs and enhancing strategic flexibility and cost stability.

**Skills and Tools Used:**
- **Data Sourcing and Extraction**
  - Used external data sources like the Bureau of Economic Research to obtain large-scale zip code distance data. A custom Python script was written to extract relevant data for the Owatonna, MN zip code, making it manageable for analysis.
- **Cost Analysis and Modeling**
  - Conducted detailed cost modeling, factoring in expenses such as wages, fuel, benefits, and lodging for in-house drivers. This helped to accurately determine the per-mile cost for internal freight operations compared to third-party carriers.
- **Data Cleansing and Transformation**
  - Cleaned and structured raw data from external sources to ensure it was usable in Excel, facilitating accurate calculation of distances and costs. Data transformation allowed for meaningful analysis and comparison of costs.
- **Python Scripting for Data Processing**
  - Developed a custom Python script to filter a massive dataset of 30+ billion rows. The script extracted the necessary data points relevant to the analysis, allowing for efficient processing without overloading Excel.
- **Excel Analysis and Calculations**
  - Used advanced Excel functions to calculate key metrics like cost per mile, potential savings, and cost comparisons. Excel’s built-in formulas and data visualization tools provided clarity for decision-making.
- **Economic and Regional Data Integration**
  - Incorporated regional economic data, such as fuel prices and labor costs from Minnesota State websites, to make the analysis region-specific and ensure more accurate cost predictions for in-house operations.

[View Project](Data-Driven-Insights-Business-Operations-Analysis-Portfolio/company_vs_3rd_party_freight_model)

## Project 3: Cost Optimization for Installation Operations: In-House vs. Third-Party

**Description:**  
The Cost Optimization for Installation Operations project aimed to determine whether the company would benefit from hiring its own installers within a specific state or continue using third-party installers. The analysis relied on existing order revenue data and third-party installation costs, including travel expenses.

Since the company did not track line-item costs per order, statistical sampling was applied to estimate travel expenses incurred by third-party installers. Using Power BI, a heatmap was created to identify "hot spots" for installations over the past three years, enabling a geographic analysis of where hiring local installers could yield the most savings.

To further assess the viability of in-house installation, data from the Bureau of Economic Research was utilized to calculate travel distances for each order, factoring in hot spot locations. With travel costs reduced, the project then considered the additional expenses of hiring unionized installers, including benefit costs and unemployment taxes.

Despite a potentially more efficient logistical model with in-house workers, the analysis revealed that hiring local installers would result in a net loss of $174,000 annually. Consequently, the company decided to continue its current model of using third-party installation services.

**Key Insights:**
- **Travel Costs as a Key Factor**
  - The analysis identified that travel expenses for third-party installers were a significant contributor to overall costs, and hiring local installers could reduce these expenses.
- **Heatmap Analysis**
  - Power BI's heatmap visualization of installation data allowed for geographic identification of "hot spots," highlighting areas where local installation would lead to the greatest cost savings.
- **Cost Trade-offs**
  - While hiring local union installers would reduce travel costs, their higher hourly wages and union benefits created an overall higher cost structure, negating the travel savings.
- **Financial Impact**
  - The analysis revealed a net loss of $174,000 per year if the company switched to an in-house installation model, emphasizing the importance of thorough cost-benefit analysis when evaluating operational changes.
- **Third-Party Model Stability**
  - The conclusion to remain with the third-party installation model was based on a clear financial understanding of the trade-offs, validating the current operational approach.

## Additional Projects
- [Customer Order Volume Forecast HeatMap](additional_projects/customer_order_volume_index.html)
- [View Technology Trends Dashboard](additional_projects/technology_trends_dashboard/tech_trends_index.html)
- [3rd Party Installer Onboarding Documentation](additional_projects/3rd_party_installer_onboarding_documentation/index.html)

## Skills & Tools
- **Data Visualization:** Power BI, Python Libraries (Matplotlib, Folium), Heatmaps
- **Data Analysis & Forecasting:** SQL, Python (Pandas, NumPy), Statistical Forecasting, Predictive Analytics
- **Geospatial Analysis:** Resource Gap Identification, Territory Optimization, Delivery Planning
- **Scenario Modeling & Cost Optimization:** Scenario Modeling, Cost-Benefit Analysis, Financial Modeling
- **Project Management:** Design, Development, Testing, Deployment, Lifecycle Management
- **Operational Process Improvement:** Streamlining, Resource Allocation, Efficiency Improvements
- **Cross-Functional Collaboration:** Sales, Operations, Logistics, Stakeholder Communication
- **Technical Writing & Documentation:** User Guides, Technical Reports, Training Development
- **Supply Chain Management:** Logistics, Installation, Vendor & Supplier Management
- **Risk Assessment:** Risk Mitigation, Problem Solving, Disruption Reduction
- **Collaboration Tools:** Microsoft Office Suite, Salesforce, Project Management Tools

## About Me
- **Email:** [brandonalbers@msn.com](mailto:brandonalbers@msn.com)
- **LinkedIn:** [Brandon Albers](https://www.linkedin.com/in/brandon-albers-85ab293b)
