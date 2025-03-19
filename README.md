# **BIS15W2025_Group10**  
### **By: KB Ko, Daniel Yang, Caitlin Chan**  

## **Project Overview**  
This project explores **factors influencing the popularity and success of TV shows** over time. Using data analysis and visualization techniques, we identify key attributes such as genre, directors, stars, and audience engagement (number of votes) that impact TV show rankings.  

Presentation: https://www.canva.com/design/DAGhlY3h21A/jy3QMmoUV230S_CpMQEagA/view?utm_content=DAGhlY3h21A&utm_campaign=designshare&utm_medium=link2&utm_source=uniquelinks&utlId=h0a05de28a4

Our process involves:  
1. **Data Cleaning** – Formatting dates, separating movies from TV shows, separating directors and stars, and ensuring a tidy dataset.  
2. **Data Analysis** – Examining patterns in ratings, longevity, and audience reception. Original analysis was done in `/draft_scripts`.  
3. **Shiny App Development** – Creating an interactive web application to visualize and explore key insights dynamically. Analysis from `/draft_scripts` was combined into `Shiny_App.Rmd`.  

## **Data Description**  
- The original dataset is `movies.csv` in `/data`.
- The original TV dataset is `tv.csv` in `/data`.
- The cleaned data set containing only TV shows that we used in analysis is `tv_only.csv` in `/data`.

## **Installation & Requirements**  
To run this project, you need:  
- **R** 
- **RStudio** (recommended for execution)  
- Required packages: included in individual files.

## **Usage**  
1. **Data Cleaning**  
   - Run `clean.Rmd` to preprocess and clean the dataset. New CSV files have already been written into the `/data` directory.

2. **Perform Analysis and Launch the Shiny App**  
   - Open `Shiny_App.Rmd` in RStudio and click Run to interact with our analysis.  

## **Key Findings**  
Our analysis reveals that several factors are associated a TV show’s popularity in rankings. Specifically:

- Genre: Certain genres like history/news consistently rank higher than others.
- Number of Votes: Shows with very few and very high audience votes often correlate with higher popularity.
- Directors: Directors like Michael Dante DiMartino and S.J. Clarkson are associated with successful TV shows like Avatar: The Last Airbender and Dexter.
- Stars: Stars like Deneen Fendig and Lisa Kreuzer also star in popular TV shows like The Midnight Gospel and Dark.

## **Contributors**  
- KB Ko
- Daniel Yang
- Caitlin Chan
