# Pick the Books My Son May Like
### --Analyze Middle Grade Books on GoodReads

[GoodReads](https://www.goodreads.com/) is a website with tons of book introduction
 and reviews from users. It is used by many people to share their reading experience. 
 It's also good place to discover books might interest you.  Recently, my son has 
 moved his reading level from simple chapter books to more complex one. He is the fan
 of Roald Dahl.  He don't like Harry Potter because he feels afraid. I'd like 
 to find some books with good reviews for my son. So I searched and analyzed 
 middle grade books.

## Program Overflow

+ First part - Scraping the book information of all middle grade books from [GoodReads](https://www.goodreads.com/search?utf8=%E2%9C%93&query=middle+grade). I use the urllib library to connect to the websites, the BeautifulSoup library to collect all of the HTML, the re library for parsing the words and filtering out other markup based on regular expressions.  I stored book informations in a CSV file.  
+ Second part - Exploratory Data Analysis on scraped book information to reveal good books. Pandas, sklearn and matplotlib are used to analyze and plot the final results.

## Result
J.K Rowling's Harry Potter Series are dominant winner of popular middle grade books
with wide readers and good reviews. I found another author Rick Riordan who is unknown
to me before. In my analysis, he is a author with top one number of published books. Ronald
Dahl is the third one. 

After searching for books with both top 25% rating score and top 25% number of rating count, 
I get a [result](https://drive.google.com/open?id=1f3VGwJ-AwGLiuGS_R3wRNqzuPW4univ8)
**Percy Jackson's Greek Gods** has lower rating count and review count while pretty good 
average rating. But the low rating count may be due to the published year is 2014, 
much later than J.K.Rowling's books. Luckily, I am looking for a good book about 
Greek gods and heros for my son recently. This one will be a definitely hit.

## Future work
I will extract reviews of books of Ronald Dahl.  I will use machine learning to build
 a recommendation system to find books with similar contents or style.