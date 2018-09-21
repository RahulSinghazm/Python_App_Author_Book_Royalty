# Python_App_Author_Book_Royalty
When Book soldout then calculate royalty


# Solution Statement:
Design a ‘book’ class with title, author, publisher, price and author’s royalty as instance variables. 
Provide getter and setter properties for all variables.
Also define a method royalty() to calculate royalty amount author can expect to receive the following
royalties:10% of the retail price on the first 500 copies; 12.5% for the next 1,000 copies sold, then
15% for all further copies sold. 
 
Then design a new ‘ebook’ class inherited from ‘book’ class. Add ebook format (EPUB, PDF, MOBI etc) 
as additional instance variable in inherited class. Override royalty() method to deduct GST @12% on ebooks 
