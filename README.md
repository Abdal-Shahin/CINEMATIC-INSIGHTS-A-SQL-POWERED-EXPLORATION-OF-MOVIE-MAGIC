# CINEMATIC INSIGHTS: A SQL-POWERED EXPLORATION OF MOVIE MAGIC 
This project focuses on extracting and analyzing key data from a comprehensive movie dataset using SQL, aiming to provide valuable insights into the film industry's performance across various dimensions such as production, financials, and talent. 

## PROBLEM STATEMENT

The movie industry generates massive amounts of data, encompassing various aspects like production, revenue, ratings, and actor details across multiple studios and genres. This data is often scattered, leading to challenges in deriving meaningful insights, optimizing financial performance, and understanding industry trends. Without structured analysis, studios, investors, and stakeholders may miss critical opportunities for profitability, talent management, and understanding audience preferences. This project leverages SQL to analyze and derive key insights from a movie dataset to support informed decision-making for business growth and efficiency.

## OBJECTIVES

The project focuses on understanding the following aspects:

- Extracting insights about movie profitability and revenue generation.
- Evaluating the performance of movie studios like Marvel and the Bollywood industry.
- Understanding audience preferences.
- Gaining insights into actors' contributions to the industry.
- Analyzing ratings and financial performance across various years.

## SCHEMA AND ENTITY RELATIONSHIP DIAGRAM (ERD)

Here's the ERD created for this project.
<p align="center">
  <img src="https://github.com/user-attachments/assets/7b5e184b-f5f5-4383-b2c2-e8e47f729b18" alt="Model">
</p>


## INSIGHTS

### INDUSTRY INSIGHTS
**1**. Industry-wise total movies
<p align="center">
  <img src="https://github.com/user-attachments/assets/f38d8544-b6de-4fcd-9308-d166aa913c6f" alt="1" />
</p>

**2**. Print all distinct movie studios in the Bollywood industry
<p align="center">
  <img src="https://github.com/user-attachments/assets/a91fa1a9-6b30-472b-aa95-b6705f707a40" alt="5" />
</p>

**3**. Select all movies whose release year is 2018, 2019, or 2022
<p align="center">
  <img src="https://github.com/user-attachments/assets/ae68c9fb-19d3-49cd-a474-9f4db77e0aa7" alt="8" />
</p>

**4**. Print all the years where more than 2 movies were released
<p align="center">
  <img src="https://github.com/user-attachments/assets/5511ccb0-47cb-42cf-ac7a-1828c1d0f337" alt="16" />
</p>


### MOVIE STUDIOS AND PRODUCTION
**1**. Print all titles and release year for all Marvel Studios movies
<p align="center">
  <img src="https://github.com/user-attachments/assets/04884a00-b40f-4784-a689-2640b2ebc620" alt="2" />
</p>

**2**. Print all movies where we don't know the value of the studio
<p align="center">
  <img src="https://github.com/user-attachments/assets/f7c4ccdc-7aa3-4fda-8d9b-8ab1ad6853b7" alt="6" />
</p>

**3**. Count the number of movies released by a given production studio
<p align="center">
  <img src="https://github.com/user-attachments/assets/f21587f6-acc6-4ae5-8f62-720066058a73" alt="14" />
</p>

**4**. Find the profit of all Bollywood movies and sort them by profit amount (in millions)
<p align="center">
  <img src="https://github.com/user-attachments/assets/64aaa710-c1e7-4cf7-851e-1c731b9f29e3" alt="22" />
</p>

**5**. Print the min, max, and avg rating of Marvel Studios movies
<p align="center">
  <img src="https://github.com/user-attachments/assets/163365e2-da36-433b-872a-f42cdbb274fd" alt="13" />
</p>

### FINANCIAL PERFORMANCE
**1**. Print profit for every movie

**2**. Print revenue of all movies in INR currency

**3**. Print revenue in millions

**4**. Find profit for all Bollywood movies

**5**. Movies that produced 500% profit and their rating was less than average rating for all movies

### MOVIE RATING & PERFORMANCE
**1**. Movies with a rating between 6 and 8

**2**. Top 5 Bollywood movies as per IMDb rating

**3**. Select movies starting from the second-highest rating Bollywood movie till the next 5 movies

**4**. Select the highest and lowest IMDb rating for Bollywood movies

**5**. What is the average rating of movies per studio and order them by average rating in descending order

**6**. Select all movies whose rating is greater than any Marvel movie's rating

**7**. Select all movies whose rating is greater than all Marvel movie ratings

### ACTORS AND TALENT
**1**. Calculate the age of each actor and print actor name, birth year, and age

**2**. Show comma-separated actor names for each movie

**3**. Print actor name and all the movies they are part of

**4**. Print actor name and how many movies they acted in

**5**. Select all actors whose age is greater than 70 and less than 85

**6**. Select actors who acted in any of these movies (101, 110, 121)

**7**. Get the actor ID, actor name, and the total number of movies they acted in

### SPECIFIC QUERIES
**1**. Print all movies that have "Avenger" in their name

**2**. Print the year when the movie "The Godfather" was released

**3**. How many total movies do we have in our movies table?


