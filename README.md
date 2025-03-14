# SleepData-DSA210Project

## **Project Overview**  
Ever wondered how daily habits influence sleep? I have too. In this project, I’ll be tracking my **physical activity, nutrition, caffeine intake, and screen time** to analyze their impact on **sleep onset time, duration, and quality**. By collecting and analyzing my own data using data science techniques, I’ll uncover what truly helps—or hinders—my sleep.  

The goal? To move beyond guesswork, identify patterns backed by data, and optimize my habits for better rest and more energized mornings.

---

## **Objectives**  
1. **Understand the Key Factors Affecting Sleep** – Identify which daily habits (physical activity, nutrition, caffeine intake, and screen time) have the most significant impact on sleep quality and duration.
     
2. **Analyze the Relationship Between Physical Activity and Sleep** – Examine whether exercise and commuting patterns contribute to better or worse sleep outcomes.
   
3. **Evaluate the Role of Nutrition** – Investigate how carbohydrate, sugar, and meat consumption influence sleep patterns, including onset time and restfulness.
    
4. **Assess the Effects of Technology Use** – Determine whether extended screen time, particularly before bedtime, disrupts sleep quality and duration.
   
5. **Use Data to Make Informed Adjustments** – Based on insights from the analysis, identify potential lifestyle changes that could improve sleep efficiency.

---

## **Motivation**  
Sleep is **everything**. It affects my energy, mood, focus, and overall well-being. But with so many things pulling at my attention—late-night Netflix, caffeine, workouts—how do I know what’s really affecting my sleep? Instead of relying on random advice, I want **hard data**.  

This project is personal. I want to stop waking up feeling groggy and start using science to take control of my rest. If I can **pinpoint the habits that improve my sleep**, I can make smarter choices every day—not just for better sleep, but for a better life.  

---
## Hypothesis

**Null Hypothesis (H₀):**  
There is no significant relationship between daily habits (physical activity, nutrition, caffeine intake, and screen time) and sleep quality. Changes in these habits do not significantly affect sleep duration or quality.  

**Alternative Hypothesis (H₁):**  
There is a significant relationship between daily habits and sleep quality. Variations in physical activity, nutrition, caffeine intake, and screen time have a measurable impact on sleep duration and quality.

## Dataset
- **Date** – The specific day of the record  
- **Physical Activity**  
  - Exercise Duration(walking, fitness) (minutes)    
- **Nutrition**  
  - Carbohydrates (g)  
  - Sugar (g)  
  - Meat Consumption (g)  
- **Caffeine Intake**  
  - Total caffeine intake (mg)  
- **Screen Time**  
  - Computer Usage (minutes)  
  - Phone Usage (minutes)  
- **Sleep Data** (from **Sleep Monitor** app)  
  - Total Sleep Duration (hours)  
  - Deep Sleep Duration (hours)  
  - Sleep Efficiency (%)  
  - Number of Awakenings  
- **Self-Assessed Metrics**  
  - Day Difficulty (1-10)  

Data will be logged daily in an Excel sheet and preprocessed for analysis. Outliers due to illness, unusual schedules, or other disruptions will be flagged for review.  

---

## **Tools and Technologies**  
To dig deep into my data, I’ll be using:  

- **Python** – The magic wand for data science!
  
- **Pandas** – Cleaning and organizing my messy data.

- **Matplotlib & Seaborn** – Making beautiful charts to actually see what’s going on.
  
- **SciPy & Statsmodels** – Running stats tests to separate facts from coincidences.   

---

## **Analysis Plan** 

## Data Collection  
- Import daily Excel records into a Pandas DataFrame and preprocess the data by handling missing values and standardizing units.
  
## Visualization  
- Use scatter plots, heatmaps, and time series plots to explore relationships between variables.  
- Examples include:  
  - Scatter plot of protein intake vs. Bench Press performance  
  - Heatmap showing correlations between all variables  
  - Time series plot comparing performance trends over three months  

## Hypothesis Testing  
- Test hypotheses like:  
  - **H₀:** Daily habits have no effect on Bench Press performance.  
  - **Hₐ:** One or more daily variables significantly impact Bench Press performance.  
- Run regression analysis to identify the strongest predictors of progress.  

## Trend Analysis  
- Investigate patterns in performance over time, identifying peaks or plateaus.  
- Analyze how body weight fluctuations and day-to-day difficulty ratings correlate with performance trends.    

---

## **Conclusion**  
By the end of this project, I’ll have **real data-backed answers** about my sleep. I’ll know exactly what **helps** me get better rest and what **hurts** it. No more random guessing—just **clear, data-driven strategies** for waking up feeling refreshed and ready to go!  

This isn’t just about sleep—it’s about **understanding how my daily choices impact my life** and using data to make smarter, healthier decisions. 
