# ideas-overflow
This is an overview of the projects I have worked on individually and at UCD as part of my MSc in Business Analytics degree. 

# Sample Sales Dashboard

This was a training project that I picked up and worked on in PowerBI. Using a sample US company's sales data, I constructed a simple dashboard for business users to be able to get a quick understanding of the sales data across time, by customer type, and by region. 

![Example 2](https://github.com/user-attachments/assets/9e50dc10-7352-49ee-8344-c462b7903c2d)

At the top, a years slicer is customizable to select the year the user wants to view more information about. On the upper right corner, the user can control which state to get sales information on.

![Example 3](https://github.com/user-attachments/assets/f8dca7fd-fab2-4aab-862f-d6bd5f663750)

The monthly sales chart provides information comes with its own custom tooltip that provides more detailed information such as YTD sales, MoM change and MoM/YoY change (how sales different from the same month in the previous year)

![Example 4](https://github.com/user-attachments/assets/8c6efaaf-7e4a-4be4-85a9-e46c51e6d083)

The map chart comes with information about the state sales data.

# Netflix Release Running Total

This exercise was inspired by HowtoPowerBI's sample exercises, with the  task of taking a dataset of Netflix releases (both movies and TV shows) and creating a running total for it. Built on PowerBI, the data was cleaned up to allow for the same item to have multiple release countries and multiple genres. This means that clicking on a specifc genre or a specifc country is possible to get more information on how many other releases fit this. The dashboard also includes a chart to showcase the different release ratings as well.

![Example 5](https://github.com/user-attachments/assets/a6efb252-d28e-49f6-9b56-dacb52e0d98e)

The dashboard is easy to navigate, and is color-coded to be simple to understand. Slicer at the top of the dashboard allow users to focus on values for movies or show, and clicking a specific country, rating or genre allows the user to see more detailed information about that specific subset of data.

![Example 7](https://github.com/user-attachments/assets/94213d45-60e9-419a-bb94-d172eba6ac53)
![Example 6](https://github.com/user-attachments/assets/920c3a3b-64f4-4916-b7f5-0b1ef686d915)

All charts come with their very own custom tooltips.

# Bucket Getter - NBA Dashboard 
Tableau Public Link: [Click me!](https://public.tableau.com/app/profile/murhaf.abdalqader/viz/BucketGetter-NBADashboard/LandingPage?publish=yes)

For Sports Analytics module, as part of the UCD MSc in Business Analytics Degree. This was built with Python, Excel, Tableau Prep and Tableau. 
The final data that the user sees through the tool is sourced from 4 different sources: Vladislav Shufinskiy’s Play-by-Play Dataset on Kaggle, Nathan Lauga’s Team Game Results & Performance on Kaggle, 
NBA’s Player Profile Repository and the NBA’s Player’s Stat Page.
- Bucket Getter is a powerful NBA dashboard tool designed to provide comprehensive insights into player performance, shot details, and team analysis.
  By leveraging shot detail data and player season data, along with advanced statistical techniques such as Monte Carlo simulation,
  Bucket Getter offers users a deeper understanding of the game and helps teams, analysts, and fans make informed decisions.
  It offers users the ability to make data-driven decisions, evaluate player contributions, and assess a team's likelihood of winning at any given moment.
  
![image](https://github.com/murhaf-abdalqader/ideas-overflow/assets/148060625/3386b617-fc8a-4f81-8c92-d63f488a6eb6)


- Bucket Getter offers a dedicated team-focused view for team performance and analysis. This feature utilises a Monte Carlo simulation,
  which is a statistical technique that calculates probabilities through repeated random sampling. 
  By applying 10, 5, and 3 game rolling averages, the tool estimates a team's likelihood of winning a game at any given moment.
  It provides information on what *already* happened, the result of the game, and statistical box score information including shooting percentages, assists and rebounds of the game.
  
![image](https://github.com/murhaf-abdalqader/ideas-overflow/assets/148060625/30f1062a-351f-4725-a903-2be89a9d0579)


- The player insights page in Bucket Getter uses real life player records, and it incorporates detailed shot data and tendency information,
  including: shot location, shot range (e.g., layup, mid-range, three-pointer), shot outcomes (made or missed), and region of the court.
  It also integrates player box statistics data, allowing users to analyse individual player performance for an entire season.
  
![image](https://github.com/murhaf-abdalqader/ideas-overflow/assets/148060625/85e3a440-17cd-4af0-908d-aeef6b795f6c)


  # Flight Delay Decision Support System (DSS) 
  Tableau Public Link: [Click me!](https://public.tableau.com/app/profile/murhaf.abdalqader/viz/MIS41040Team30/Overview)

  For Business Decision Support Systems module, as part of the UCD MSc in Business Analytics Degree. This was built with Python, Excel, Tableau Prep and Tableau. 
The final data that the user sees through the tool is sourced from an open source US flight delay dataset.
 
- The Flight Delay DSS is an advanced decision support system meticulously crafted to uncover the root causes behind flight delays for commercial flights across the United States.

![image](https://github.com/murhaf-abdalqader/ideas-overflow/assets/148060625/3b8147b2-27a4-4bc0-b7f3-1676c95646e7)

- In the "States" view, you will be provided with a nuanced understanding of delays, offering detailed insights into state-specific delays. This feature facilitates direct comparisons between states and their respective airports.

![image](https://github.com/murhaf-abdalqader/ideas-overflow/assets/148060625/8f85852a-410a-4400-85f9-68ce355e4ac9)

- In the "Airlines" view, gain valuable insights into delay patterns based on operating airlines. This section provides users with additional information about the origins of delays corresponding to different airlines.
  
![image](https://github.com/murhaf-abdalqader/ideas-overflow/assets/148060625/cc4cce12-52a3-4d8e-bccb-8cbc4a76aa19)

- Explore the impact of demographics and seasonal variations on flight delays with the DSS's dedicated demographics and season view. This feature enriches the analysis by considering broader contextual factors.

![image](https://github.com/murhaf-abdalqader/ideas-overflow/assets/148060625/89d87dae-a7a5-45d4-b1e1-605d1174fcaf)

- Delve into the quantitative aspects of delays with the "Descriptive Measures" view. The DSS provides key metrics such as mean delay, median delay, and standard deviation. These measures offer a comprehensive overview of delays across all states and airlines, enhancing the analytical depth of the tool.


  
