# Hadoop and Map Reduce

## Requirements

We need:

	- Python 2.7
	- Virtualenv (pip install virtualenv && virtuale envMyEnv && source envMyEnv/bin/activate) 
	- MrJob (pip install mrjob)
	- Download MovieData DB (100K) http://grouplens.org/datasets/movielens/ 
	- Put the unzip folder into src-movies folder


Check -> https://github.com/alexcomu/big-data-basics to read a simple introduction on MapReduce and Hadoop.


## Example

### 01_rating_counter.py

Count occurences of rating value from movie DB.

### 02_avarage_friends.py

Calculate For each Age the Avarage of friends. Data (csv) Structure:

	ID, Name, Age, Number of Friends

How to Run:

	$ python filename.py CSV-SOURCE.csv > result.txt


### 03_temperature_extreme.py

Check for each location the minimum or maximum temperature.

Src file:

     03_temperature.csv

How to Run:

     $ python filename.py CSV-SOURCE.csv > result.txt
     
     
### 04_word_frequency.py

Calculate the word frequency from a book source.

How to Run:

     $ python filename.py CSV-SOURCE.csv > result.txt
