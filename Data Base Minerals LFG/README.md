# Minerals Database

The Minerals Database covers more than a hundred minerals and details about their:
* color
* chemical formula
* sources. Which countries in the world extract them.
* zodiac signs. Yes, every single mineral has some corresponding zodiac sign which it influences very well! :) 

The database for minerals is created by This database was part of my school project. Thorough documentation can be found in the
Manifest folder.

The architecture of the database is not stunningly complex and is as follows:
![Minerals DB](https://github.com/kdx2/Databases/blob/master/Data%20Base%20Minerals%20LFG/Manifest/Relat.jpg)

## Queries
There are a couple of Insert (Append) quieries, on of type Cross Tab, Alter Add, Alter Column..., Create Table query, Delete query
(which deletes Moldova from the table of Source), a parameter query, selectiva and Totals, which is combined with Update.
All made in SQL.
For the creation of these queries were used: SELECT, FROM, WHERE, GROUP BY, SORT BY, aggregate functions and others.


## Installation and execution:
Just git clone the repo and run the Minerals.accdb file. 
__Make sure there is an installed MS Access of the machine you are trying to run it__.

### Side-notes
It so not made with data-scrapping in another automated manner. I had a book by an author who is referenced in the documentation located
inside the Manifest folder.

For now the whole database and documentation are not translated into English. Lately I am busy and I won't translate the database but
soon at some point I may do that to the documentation.

Regardless the resolution. Back in the day, when I was creating the project MS Access did not allow for adjustable screen resolution. 
All that means is, the database has a static UI, which does not look in the same way at any computer screen, as it was made to only for
the one on which the project was developed. It is likely some buttons to be a bit shuffled and even more likely there to be big gaps
without buttons as newer computers/laptops in general have 2-3 times better resolution nowadays.
