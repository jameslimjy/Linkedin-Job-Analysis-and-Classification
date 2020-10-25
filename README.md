# Linkedin-Job-Analysis-and-Classification

This is a personal project that incorporates the following elements:
- Web scraping
- Data cleaning
- EDA
- Classification
    - Naive Bayes classifier
    - Logistic Regression classifier
    - Deep Learning: Keras LSTM classifier

### Web Scraping
I built a web scraper using Selenium and Beautiful Soup to scrape information from Linkedin. The web scraper is a ipynb file named **Scraper Function** in this repository. From what I read online, Linkedin's API is pretty restrictive in terms of the amount of information it allows you to attain. Hence, I opted to scrape the information myself manually. Anyways, I wanted to practice building a scraper too :) 

I collected the following information:
- Job title
- Company name
- Country
- When the job opening was posted
- Number of applicants
- Job hyperlink
- Job description

Scraping Linkedin has its challenges too. Linkedin, like many other websites, uses an *infinity scroll*, meaning instead of clicking a button to navigate to the next page, you had to scroll to the bottom of the current page and wait for the next page to *append* to the existing page. This was a slight inconvenience but it was overcame. What could not be overcome, however, was Linkedin's anti-scraping feature, which allowed a user to only view the first 1000 jobs of a search. But it was alright for me as I felt that 1000 results per search was sufficient.