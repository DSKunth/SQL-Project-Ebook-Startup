# SQL-Project-Ebook-Startup
## Overview
The coronavirus took the entire world by surprise, changing everyone's daily routine. City dwellers no longer spent their free time outside, going to cafes and malls; more people were at home, reading books. That attracted the attention of startups that rushed to develop new apps for book lovers.

You've been given a database of one of the services competing in this market. It contains data on books, publishers, authors, customer ratings and reviews of books. This information will be used to generate a value proposition for a new product.

### Description of tables
**books**
- book_id
- author_id
- title
- num_pages (number of pages)
- publication_date
- publisher_id

**authors**
- author_id
- author

**publishers**
- publisher_id
- publisher

**ratings**
- rating_id
- book_id
- username (the name of the user who rated the book)
- rating

**reviews**
- review_id
- book_id
- username (the name of the user who reviewed the book)
- text

### Data Diagram
![image](https://user-images.githubusercontent.com/98457852/187034472-711f5dbe-d445-4dfc-8275-a4ba83622ade.png)

## Goal
Based on the given data, the goal is to create a product value proposition that articulates the product's purpose, features and differentiators while taking into account the customer's problems, needs and wants. This is to ensure that target prospects will read more about the company and understand what they will get out of the products and services.

## Tasks
- Find the number of books released after January 1, 2000.
- Find the number of user reviews and the average rating for each book.
- Identify the publisher that has released the greatest number of books with more than 50 pages (this will help you exclude brochures and similar publications from your analysis).
- Identify the author with the highest average book rating (look only at books with at least 50 ratings).
- Find the average number of text reviews among users who rated more than 50 books.
