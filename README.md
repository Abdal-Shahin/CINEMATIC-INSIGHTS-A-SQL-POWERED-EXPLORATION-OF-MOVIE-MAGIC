# CINEMATIC INSIGHTS: A SQL-POWERED EXPLORATION OF MOVIE MAGIC 
This project focuses on extracting key data from a comprehensive movie dataset using SQL, aiming to provide valuable insights into the film industry's performance across various dimensions such as production, financials, and talent. 

![pexels-nathan-engel-50858-436413](https://github.com/user-attachments/assets/55d39506-0f00-4f80-9157-c14834c1861d)


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
<p align="center">
  <img src="https://github.com/user-attachments/assets/ac18bb5d-b497-4da5-98b4-c8534e469cce" alt="18" />
</p>

**2**. Print revenue of all movies in INR currency
<p align="center">
  <img src="https://github.com/user-attachments/assets/356a0de4-fdc6-4826-8576-41a0f87e8457" alt="19" />
</p>


**3**. Print revenue in millions
<p align="center">
  <img src="https://github.com/user-attachments/assets/3686f47d-b40f-4786-8f4d-7a28476b6a70" alt="20" />
</p>

**4**. Find profit for all Bollywood movies
<p align="center">
  <img src="https://github.com/user-attachments/assets/bfe579b5-f1f0-4bfe-a911-4e60625fc71f" alt="21" />
</p>

**5**. Movies that produced 500% profit and their rating was less than average rating for all movies
<p align="center">
  <img src="https://github.com/user-attachments/assets/d54e6407-cbce-4dc2-8463-7e124b3a5f6a" alt="31" />
</p>

### MOVIE RATING & PERFORMANCE
**1**. Movies with a rating between 6 and 8
<p align="center">
  <img src="https://github.com/user-attachments/assets/1785cb6a-3aaf-4a29-ac20-a36418ae5f84" alt="7" />
</p>

**2**. Top 5 Bollywood movies as per IMDb rating
<p align="center">
  <img src="https://github.com/user-attachments/assets/b96be754-7f78-4f01-9c85-14aa004bb633" alt="9" />
</p>

**3**. Select movies starting from the second-highest rating Bollywood movie till the next 5 movies
<p align="center">
  <img src="https://github.com/user-attachments/assets/559d1c5c-a99a-411b-92b1-1d224e74b8ad" alt="10" />
</p>

**4**. Select the highest and lowest IMDb rating for Bollywood movies
<p align="center">
  <img src="https://github.com/user-attachments/assets/2a63983d-06fd-4d90-888e-42f5c484f94f" alt="12" />
</p>

**5**. What is the average rating of movies per studio and order them by average rating in descending order
<p align="center">
  <img src="https://github.com/user-attachments/assets/55395947-7a14-4cdc-a919-8ae9bdcb00d4" alt="15" />
</p>

**6**. Select all movies whose rating is greater than any Marvel movie's rating
<p align="center">
  <img src="https://github.com/user-attachments/assets/b12f5a4a-d324-47b2-a3d8-65a23bda994d" alt="28" />
</p>

**7**. Select all movies whose rating is greater than all Marvel movie ratings
<p align="center">
  <img src="https://github.com/user-attachments/assets/eb1ba00a-1500-4003-8ab5-787d5dfff08e" alt="29" />
</p>


### ACTORS AND TALENT
**1**. Calculate the age of each actor and print actor name, birth year, and age
<p align="center">
  <img src="https://github.com/user-attachments/assets/d133aca1-066d-432b-881b-b6389e78b75f" alt="17" />
</p>

**2**. Show comma-separated actor names for each movie
<p align="center">
  <img src="https://github.com/user-attachments/assets/0775824b-87d3-4e3b-8cda-99b9fc22d406" alt="23" />
</p>

**3**. Print actor name and all the movies they are part of
<p align="center">
  <img src="https://github.com/user-attachments/assets/ff2711ac-1e7c-4d7b-8046-1415185a007d" alt="24" />
</p>

**4**. Print actor name and how many movies they acted in
<p align="center">
  <img src="https://github.com/user-attachments/assets/d7bf407a-435e-4af8-a65d-05b8de4bb046" alt="25" />
</p>

**5**. Select all actors whose age is greater than 70 and less than 85
<p align="center">
  <img src="https://github.com/user-attachments/assets/33c168e8-6065-4145-b809-3d5f112d4d26" alt="26" />
</p>

**6**. Select actors who acted in any of these movies (101, 110, 121)
<p align="center">
  <img src="https://github.com/user-attachments/assets/b6674186-f9bb-4c2e-9637-9c0b49d773e9" alt="27" />
</p>

**7**. Get the actor ID, actor name, and the total number of movies they acted in
<p align="center">
  <img src="https://github.com/user-attachments/assets/4bf28376-a9e8-4721-8f77-11c730c1ed7b" alt="30" />
</p>

### SPECIFIC QUERIES
**1**. Print all movies that have "Avenger" in their name
<p align="center">
  <img src="https://github.com/user-attachments/assets/d9444ad3-ad1e-4741-afd0-5256c2586a25" alt="3" />
</p>

**2**. Print the year when the movie "The Godfather" was released
<p align="center">
  <img src="https://github.com/user-attachments/assets/d2dc1355-355e-4b59-bbfe-4d218cfc62ec" alt="4" />
</p>

**3**. How many total movies do we have in our movies table?
<p align="center">
  <img src="https://github.com/user-attachments/assets/51748392-8292-4415-8a0b-d41bf2b989c8" alt="11" />
</p>

