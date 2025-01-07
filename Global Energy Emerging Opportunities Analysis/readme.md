# Global Energy Emerging Opportunities
**Author:** Facundo Espina

---

## **Project Overview**
This project analyzes the global energy landscape to identify emerging opportunities and risks in renewable and conventional energy sectors. Using a comprehensive dataset spanning over 22,000 records and 129 variables, we explore energy consumption, production, and renewable growth trends across different regions and countries. The insights will help **InvEnergy**, a global investment firm, make informed decisions about optimizing its portfolio.

---

## **Business Case**
### **Client: InvEnergy**
InvEnergy is a global investment firm focused on the energy sector. As the industry shifts towards sustainability, the firm seeks to:
- Identify regions with significant growth potential.
- Manage risks associated with energy security and policy changes.
- Balance investments in both renewable and conventional energy sectors.

By leveraging data analytics, InvEnergy aims to:
- Understand global energy trends.
- Assess regional risks and opportunities.
- Optimize investments in renewable and traditional energy sectors.

---

## **Key Business Questions**
1. **Global Energy Overview**: What is the energy consumption mix for different regions, and which are most reliant on fossil fuels or renewables?
2. **Energy and Economic Context**: How does energy consumption compare to economic metrics like GDP or population?
3. **Global Energy Transition**: Which countries are leading the shift from fossil fuels to renewable energy?
4. **Investment Risk Assessment**: Which countries have significant gaps between energy consumption and production, indicating risks?
5. **Renewable Energy Growth**: Which European countries have shown the most growth in solar and wind energy production in the last five years?
6. **Energy Consumption Trends**: What are the long-term energy consumption trends in key regions?
7. **Emerging Renewable Markets**: Which countries are showing early signs of adopting renewable energy?

---

## **Dataset**
- **Source**: [Kaggle - World Energy Consumption](https://www.kaggle.com/datasets/pralabhpoudel/world-energy-consumption)
- **Description**: 
  - Tracks country-level energy production, consumption, and generation from various sources like fossil fuels, solar, wind, and biofuels.
  - Includes economic indicators like GDP, population, and greenhouse gas emissions.
  - Covers the years 1900–2022, with recent focus on the past 30 years.
- **Size**: 22,000+ records, 129 variables.

---

## **Key Insights**
### **1. Global Energy Transition**
- **Leading Countries**: Hong Kong, Israel, South Africa, and Estonia exhibit the fastest growth in renewable energy share.
- **Top Producers**: China, the U.S., and Brazil dominate in absolute renewable energy production growth.
- **Emerging Players**: Countries like India and Vietnam are showing rapid progress in renewables.

### **2. Investment Risk Assessment**
- Countries like **China, India, South Korea**, and **Japan** face significant energy production gaps, signaling potential energy security risks but also opportunities for renewable investments.
- **Europe**: Germany, France, and Italy show moderate energy gaps, suitable for efficiency and renewable projects.

### **3. Renewable Energy Growth**
- **Solar Growth Leaders**: Belarus, Estonia, and Poland have shown remarkable solar energy growth.
- **Wind Growth Leaders**: Luxembourg, Germany, and Finland lead in wind energy production growth.

### **4. Energy Consumption Trends**
- **Asia**: Shows the strongest growth, projected to surpass 100,000 TWh by 2030.
- **North America & Europe**: Stable or declining energy consumption patterns, with focus shifting to energy efficiency.
- **Africa**: Emerging as a key market with growing energy demand.

### **5. Emerging Markets**
- **Key Countries**: South Africa, India, Vietnam, and Poland show early adoption of renewable technologies with high growth rates but low renewable shares.

---

## **Key Visualizations**
1. **Global Energy Consumption Heatmap**: Shows primary energy consumption by country.
2. **Renewable Growth Leaders**: Highlights top countries by renewable energy share and absolute growth (TWh).
3. **Energy Production vs. Consumption Gaps**: Identifies countries with significant energy shortfalls.
4. **Regional Consumption Trends**: Long-term trends for Asia, Europe, North America, and Africa.
5. **Emerging Renewable Markets**: Interactive scatterplots showing renewable growth and adoption over time.

---

## **Technical Highlights**
### **Tools & Libraries**
- **Data Analysis**: Python, Pandas, NumPy.
- **Visualizations**: Matplotlib, Seaborn, Plotly, Geopandas.
- **Statistical Analysis**: Scikit-learn for regression and forecasting.

### **Data Processing**
- Handled missing values using forward/backward fill methods.
- Reduced timeframe to focus on relevant years (1990–2022).
- Scaled and normalized data to facilitate meaningful comparisons.

### **Feature Engineering**
- Created new metrics like **renewables growth percentage**, **energy gap percentage**, and **renewables share in total energy**.

---

## **Conclusions**
1. **Renewable Adoption**: Focus investments in countries with high growth potential, such as India, South Africa, and Vietnam.
2. **Energy Gaps**: Address risks in countries with significant energy shortfalls, such as China, India, and South Korea.
3. **Regional Priorities**:
   - **Asia**: Invest in large-scale renewable infrastructure to meet rising demand.
   - **Europe**: Focus on innovation in energy storage and efficiency.
   - **Africa**: Target early-stage investments in renewable energy projects.

---

## **Recommendations**
- **Short-Term**: Invest in mature markets like Europe for green technology innovation.
- **Long-Term**: Prioritize emerging markets in Asia, Africa, and Latin America for renewable infrastructure development.
- **Risk Mitigation**: Focus on countries with significant energy gaps, offering solutions like energy storage and grid modernization.

---

## **References**
- **Dataset**: [Kaggle - World Energy Consumption](https://www.kaggle.com/datasets/pralabhpoudel/world-energy-consumption)
- **Documentation**:
  - [Scikit-learn](https://scikit-learn.org)
  - [Seaborn Visualization Guide](https://seaborn.pydata.org)

