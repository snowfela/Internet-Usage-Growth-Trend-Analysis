# 🌐 Our World Connected

## Overview
This project explores the **global expansion of the Internet** and evaluates how close humanity is to becoming a **fully connected digital world**. Using real-world datasets on internet usage and historical world population, it analyzes trends, growth rates, and the rapid evolution of global connectivity over time.

## Objectives
- Analyze the **growth of Internet users** from 1990 to 2024.  
- Compare Internet user growth to **world population trends**.  
- Calculate the **percentage of the global population** connected to the Internet over time.  
- Visualize the **rise of global connectivity** and discuss its implications for a connected future.

## Datasets
The project uses two key datasets:
- `world-internet-users.csv` — Contains the number of Internet users worldwide per year (1990–2024).  
- `historical-world-population.csv` — Provides historical estimates of global population dating back to 10,000 BCE.

## Key Steps and Analysis

### 1. Loading and Inspecting the Data
- Imported data using **pandas** and **matplotlib**.  
- Displayed the Internet user data containing 35 rows (1990–2024).  
- Observed initial values:  
  - 1990 → 3 million Internet users.  
  - By 1997, users exceeded 100 million.

### 2. Analyzing Internet Growth
- Used the `query()` method to identify when Internet users surpassed 100 million.  
- Determined that the milestone was reached in **just 7 years (1997)** — from 3 million in 1990 to 100 million in 1997.  
- Demonstrated the exponential nature of early Internet adoption.

### 3. Integrating Population Data
- Loaded the **historical world population** dataset to contextualize Internet growth relative to total population.  
- The dataset spans thousands of years, with modern estimates aligning with the Internet data.

### 4. Merging Datasets
- Merged both datasets using a **left join** on the `year` column to align Internet usage with population size.  
- Maintained all Internet data from 1990 to 2024 while aligning available population values.  
- Resulting DataFrame contained columns for `year`, `internet_users`, and `population`.

### 5. Computing Internet Penetration
- Calculated the percentage of the global population using the Internet:  
  \[
  \text{Internet Penetration} = \frac{\text{Internet Users}}{\text{World Population}} \times 100
  \]
- Analyzed how this percentage evolved year by year.  
- Noted the **dramatic increase in connectivity** over three decades.

### 6. Visualization
- Created **line plots** using `matplotlib` to visualize:
  - Internet users over time.  
  - Internet penetration as a percentage of the world population.  
- Displayed clear trends showing the **exponential rise of Internet adoption** and the narrowing digital divide.

## Tools & Libraries
- **Python**  
- **Pandas** for data manipulation and analysis  
- **Matplotlib** for visualization  
- **Google Colab** for running and visualizing code interactively  

## Key Insights
- Internet users grew from **3 million (1990)** to **billions by 2024**, marking one of the fastest technology adoptions in human history.  
- By the mid-2010s, **more than half of the global population** had Internet access.  
- The merge of Internet and population data reveals how **connectivity parallels global development and innovation**.  
- Despite impressive growth, disparities in access remain — particularly across regions and income levels.

## Author
Developed as a **data-driven exploration of global Internet connectivity**, combining population analytics and digital adoption trends using Python and open datasets.
