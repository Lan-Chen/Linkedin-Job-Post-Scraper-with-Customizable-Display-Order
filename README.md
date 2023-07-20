# Linkedin-Job-Post-Scraper-with-Customizable-Display-Order
Scraping job posts from LinkedIn and enhancing the sorting functionality

## Why do I do so
LinkedIn is a professional networking platform with job search functionality. I am actively seeking jobs now and use it to search for data-related jobs. However, I have a very bad user experience when searching the job posts:

- Many search results are unrelated to the job title I entered.
  - They even display job post for Janitor when I search for Data Scientist, although they do have some similarities in cleaning things.
- The display order is not based on the relevance of the search results.
  - This is understandable that they have some promotions, but it will be time-consuming for me on mannual screening.
- Unable to filter or sort based on the number of applicants for each job.
  - This is a feature in an urgent need in this crazy job market, as I saw jobs can have 1000+ applicants in half a day.
- The filter on posting date is limited. Only past month, past week and past day are provided.
  - Again, since a job post can have 1000+ applicants in half a day, the minimum of 1 day is not enough.
  - Also, it will be better if I can choose any time.
- Unable to filter or sort based on the required years of experience.
  - Most of the jobs require 5+ yoe, but I am interested in those with 5- yoe.

## What are the new things
- Jobs are ordered by relevance.
  - Data-related jobs can have various job titles, therefore it will be important to define "relevance". To address this, I add a feature that can capture different titles/keywords, and it is customizable.
- Jobs are ordered by number of applicants.
- Filter on posting date is customizable.
  - 0.5 day is possible! 
- Jobs are ordered by yoe.
