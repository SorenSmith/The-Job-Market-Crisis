# The-Job-Market-Crisis

## Summary ##
Given the current uncertainty in the job market, I wanted to analyze which industries and companies are experiencing the most significant struggles, as well as whether the impact is as severe globally as portrayed in the media.

 To conduct this analysis, I obtained layoff data from 2024 through Kaggle.

 Dataset: Layoffs Data (2022-2024)

I then processed the data by cleaning and formatting it. This included:
- Removing unnecessary columns, such as List_of_Employees_Laid_Off, which contained incomplete or irrelevant data.
- Formatting numerical values for better readability, including converting percentage values to a more intuitive format.

## 🔑 Key Questions ##
This analysis aims to answer the following questions:
1. Which countries are experiencing the highest number of layoffs?
2. Which countries are seeing the lowest number of layoffs?
3. Which industries are most affected by layoffs?
4. Which companies have reported the highest number of layoffs?
5. Does the location of a company's headquarters influence layoff rates?

## 💭 Hypothesis ##
- Based on media reports, I expect North America and Europe to be experiencing the most significant layoffs.
- In contrast, I anticipate that Asian countries have been less affected by widespread layoffs.
- Industries such as crypto and travel are likely among the hardest hit, primarily due to decreased consumer spending. Manufacturing may also see significant layoffs.
- Large Corporations, such as Amazon, are expected to have higher layoff numbers compared to smaller, less prominent companies.
- I do not expect a company's headquarters locations to have a direct impact on its layoff rate.

## Executive Summary ##
Our analysis of the data indicates that the United States currently experiences the highest layoff rate globally, followed by India and several major European countries, including Germany, the United Kingdom, and the Netherlands. While Amazon, Meta (Facebook), and Tesla recorded the highest number of layoffs in 2024, the retail industry saw the most significant job cuts, followed by the consumer sector—which includes businesses that produce, distribute, and sell goods and services directly to individuals, spanning industries such as food, clothing, electronics, and entertainment. Additionally, U.S.-based companies accounted for the highest number of layoffs, suggesting that a company's headquarters location may be a contributing factor in assessing layoff risks.

Tableau [Link](https://public.tableau.com/app/profile/soren.smith/viz/TheJobMarketCrisis/Dashboard1)

![Unicorns-2](https://github.com/SorenSmith/The-Job-Market-Crisis/blob/main/The%20Job%20Market%20Crisis%20Dashboard.png)

## Deep Dive Analysis ##

# **Deep Dive Analysis: The Job Market Crisis Dashboard**

## **Overview of the Dashboard**
This dashboard presents an analysis of job layoffs across different dimensions, including:
- **Companies and their locations** (bubble chart)
- **Countries with the most and least layoffs** (bar charts)
- **Industries most affected by layoffs** (bar chart)
- **Companies with the highest number of layoffs** (bar chart)

Each visualization provides insights into the overall job market crisis and its impact on various sectors.

---

## **Deep Dive Analysis of Each Component**

### **1. Companies and Their Locations (Bubble Chart)**
- This visualization uses bubbles to represent different companies, with size likely corresponding to the number of layoffs.
- The color coding differentiates companies by country.
- **Observations:**
  - **Amazon, Google, Microsoft, Tesla, and Meta** have some of the largest bubbles, indicating high layoff counts.
  - **SAP and Philips** also appear significant but relatively smaller than big tech companies.
  - The visualization effectively shows geographical distribution but lacks precise numbers for layoff amounts without hovering.

---

### **2. Top 10 Countries with the Most Layoffs (Bar Chart - Top Right)**
- The **United States** has **over 400K layoffs**, significantly surpassing other countries.
- **India, Germany, and the UK** follow but at much lower levels.
- Other countries like **Sweden, Brazil, Canada, and Singapore** have relatively smaller layoff counts.
- The sharp contrast suggests that layoffs are disproportionately affecting the U.S. job market.

---

### **3. Top 10 Countries with the Least Layoffs (Bar Chart - Middle Right)**
- Countries like **Luxembourg, Belgium, and Ukraine** have the lowest layoff numbers, with **Bulgaria having the least**.
- Many of these countries have smaller economies, which may contribute to lower layoffs.
- Another possibility is that these regions have **stronger labor protections** or **smaller workforce sizes in affected industries**.

---

### **4. Industry with the Most Layoffs (Bar Chart - Bottom Left)**
- **Retail, construction, and transportation** lead the layoffs, each exceeding 50K job losses.
- **Tech, finance, and healthcare** follow, showing that even well-established industries are affected.
- Surprisingly, **HR, media, and subscription services** also see layoffs, hinting at shifts in digital media and business models.
- **AI and aerospace** have relatively minor layoffs, possibly indicating continued growth in these fields.

---

### **5. Companies with the Most Layoffs (Bar Chart - Bottom Right)**
- **Amazon, Meta, and Tesla** have the highest layoff counts, with each exceeding **20K+**.
- **Microsoft, Google, and Dell** are also heavily impacted, reflecting ongoing layoffs in tech.
- **SAP, a German software company**, also appears, showing that layoffs extend beyond U.S. firms.
- This chart reinforces the idea that **tech companies have been among the hardest hit** in layoffs.

---

## **Key Takeaways & Insights**
1. **The U.S. is experiencing a major layoff crisis** compared to other nations.
2. **Tech giants (Amazon, Meta, Tesla, Google, etc.) are driving the largest layoffs**, suggesting a correction in hiring after previous expansion phases.
3. **Retail, construction, and transportation are the most impacted industries**, reflecting possible economic downturn effects.
4. **Some industries, like AI and aerospace, show resilience**, possibly due to continued innovation and investment.
5. **Countries with fewer layoffs tend to have smaller economies or stronger labor protections**.

---

## **Areas for Improvement in the Dashboard**
1. **More precise numbers**: The bubble chart could include exact layoff numbers instead of requiring hover interactions.
2. **Trend analysis**: A time-series graph showing layoffs over months/years could provide deeper insights.
3. **Layoff reasons**: Including a breakdown of factors (e.g., economic downturn, restructuring, automation) would enhance understanding.
4. **Comparison with hiring trends**: Overlaying hiring data could reveal whether industries are shrinking or just restructuring.

---


