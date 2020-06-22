For this code to work, you need to have a database for that code to read so that the scraper has titles of candies to search.

The general format of the database is:
Column 1	Column 2
Suppliers	Candy Name
EX: Gustafs	EX: Anise Bears

The code will then search that querie + the word 'Ingredients'
Once the search query of 'Supplier + Candy Name + Ingredients', or 'Gustaf's Anise Bears Ingredients' is searched for, the code will return the text immediately occuring after the word Ingredients. This code will also create queries for the 5 first searches in case the first query doesn't yield results.

An example for this is:
'https://allcitycandy.com/products/dutch-licorice-bears-3Glucose
fructose syrup, sugar, water, gelatin, modified starch, ammonium chloride, molasses, color (plain caramel), liquorice root extract, maltodextrin, natural anise flavoring' 

This is extremely helpful as I've had a database of 300 labels for candy names and suppliers to find the ingredients for. I created this for the possibility that you may have another large database of names to search for as well as words that assist your query. 
