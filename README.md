# Linkedin-Job-Post-Scraper-with-Customizable-Display-Order
Scraping job posts from LinkedIn and enhancing the sorting functionality

## Why do I do so
LinkedIn is a professional networking platform with job search functionality. I am actively seeking jobs now and use it to search for data-related jobs. However, I have encountered some challenges in my user experience while searching for job posts:

- Many search results are unrelated to the job title I entered.
  - They even display job post for Janitor when I search for Data Scientist, although they do have some similarities in the aspect of cleaning things.
- The display order is not based on the relevance of the search results.
  - This is understandable that they have some promotions, but it will be time-consuming for me on mannual screening.
- Unable to filter or sort based on the number of applicants for each job.
  - This feature is urgently needed in this crazy job market, as I saw jobs can have 1000+ applicants in half a day.
- The filter on posting date is limited. Only past month, past week and past day are provided.
  - Again, since a job post can have 1000+ applicants in half a day, the minimum of 1 day is not sufficient.
  - Also, it will be better if I can choose any time.
- Unable to filter or sort based on the required years of experience.
  - Most of the jobs require 5+ yoe, but I am interested in those with 5- yoe.

## What' new
- Jobs are ordered by relevance.
  - Data-related jobs can have various job titles, therefore it will be important to define "relevance". To address this, I add a feature that can capture different titles/keywords, and it's fully customizable according to your preferences.
- Jobs can be sorted by the number of applicants.
- The filter for posting date is now customizable.
  - You can now set a filter as specific as 0.5 days!
- Jobs can be sorted by years of experience (yoe).
