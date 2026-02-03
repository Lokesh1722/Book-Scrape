Project Overview

BookScrape is a data analytics and web scraping project that extracts book information from BooksToScrape.com and analyzes pricing, ratings, availability, and category trends.   
The goal of this project is to help understand how book prices vary across categories and how ratings influence pricing in an online marketplace.    

Problem Statement

Online book marketplaces have thousands of books with different prices and ratings, making it difficult for users to identify:   
Affordable books  
Highly rated books   
Expensive or premium categories   
Trends in pricing and ratings     
This project uses web scraping and data analysis to discover meaningful insights from the book data.   

Objectives

Find the average book price across categories   
Identify most expensive and cheapest categories   
Analyze rating vs price relationship      
Check availability trends     
Understand category diversity    

Data Source

Data is scraped from:       
https://books.toscrape.com      
This is a practice e-commerce website that provides:   
Book Title   
Price 
Star Rating         
Stock Availability    
Category (Genre)     

Tools & Technologies

Python                                
Requests – to fetch webpage data           
BeautifulSoup – to parse HTML       
Pandas – data cleaning and analysis     
Matplotlib & Seaborn – data visualization             
Jupyter Notebook         

Data Collection Process

Inspect the website structure           
Send HTTP requests to fetch pages     
Parse HTML using BeautifulSoup      
Extract:  
Title  
Price 
Rating   
Availability   
Category
Handle pagination         
Store data in CSV format     

Data Cleaning

Removed missing and duplicate values     
Converted price to numeric format   
Converted ratings into numerical values        
Standardized category and availability labels   

Exploratory Data Analysis (EDA)

The following analyses were performed:       
Price distribution of books      
Average price by category  
Rating vs Price correlation         
Category-wise price comparison   
Availability vs pricing   
Outlier detection using Boxplots & KDE 
Heatmaps and correlation matrices

Key Insights

Fiction has the highest number of books        
Science and Art categories are the most expensive     
Books with higher ratings generally have higher prices      
In-stock books dominate, but rare/out-of-stock books tend to be costlier   
A balanced mix of budget and premium books exists across categories  

How to Run the Project

Clone the repository    
git clone https://github.com/your-username/book-scrape

Install dependencies  
pip install -r requirements.txt

Run the Jupyter notebooks
jupyter notebook

Conclusion

This project successfully demonstrates how web scraping and data analysis can be used to extract useful insights from an online bookstore.   
It highlights how category, ratings, and availability play a major role in book pricing and helps users understand market trends better.    
