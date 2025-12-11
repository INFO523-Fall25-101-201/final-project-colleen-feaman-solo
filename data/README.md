# Data
This project uses two datasets derived from publicly available book-rating datasets. 

## Variable Names and Descriptions:

# Books.csv
 i   Column               Description  
---  ------               ------------------------------
 0   ISBN                 unique identifier for each book
 1   Book-Title           title of the book
 2   Book-Author          author of the book
 3   Year-Of-Publication  year the book was published
 4   Publisher            company that published the book
 5   Image-URL-S          URL to a small cover image
 6   Image-URL-M          URL to a medium cover image
 7   Image-URL-L          URL to a large cover image

# Ratings.csv
 i   Column       Description
---  ------       -------------------
 0   User-ID      annonymous unique id for each user
 1   ISBN         unique identifier for each book
 2   Book-Rating  rating given to book from User_ID


## Data Types:

# Books.csv
 i   Column               Non-Null Count   Dtype 
---  ------               --------------   ----- 
 0   ISBN                 271360 non-null  object
 1   Book-Title           271360 non-null  object
 2   Book-Author          271358 non-null  object
 3   Year-Of-Publication  271360 non-null  object
 4   Publisher            271358 non-null  object
 5   Image-URL-S          271360 non-null  object
 6   Image-URL-M          271360 non-null  object
 7   Image-URL-L          271357 non-null  object

# Ratings.csv
 i   Column       Non-Null Count    Dtype 
---  ------       --------------    ----- 
 0   User-ID      1149780 non-null  int64 
 1   ISBN         1149780 non-null  object
 2   Book-Rating  1149780 non-null  int64 

