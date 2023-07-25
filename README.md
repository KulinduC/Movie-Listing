# Movie-Listing
Organizing movie data via hashtable

Usage:

g++ -Wall -Werror main.cpp Movie.cpp

./a.out

cin will wait for a command that includes "movies", "actors", "query", "table_size", "occupancy", "quit" 

The commands "movies" and "actors" expect a text file with the corresponding data to file the hashtable. 
The "query" command is followed by a movie title, or length, or genre, or actor ids 
The "table_size" command sets the size of the hashtable and "occupancy" command sets the occupancy size for the table
The "quit" command quits out of cin
