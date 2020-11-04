# PokeData

This is a personal project for SQLAlchemy Practice. By using a SQLAlchemy-derived engine, I connected my Jupyter Notebook kernel to the database that houses the most updated
dataset I have on Pokemon. The dataset goes up to order #721, which has a little under 800 rows of pokemon data. 

The last entry is Volcanion, which is a generation 6 pokemon. The current generation as of this repository's creation is generation 8. Pokemon from the Sun, Moon, Shield & 
Sword games and their information are not included. 

| UPDATE: I just added a new dataset that pushes up the order to 898. As of today, 11/4/2020, the most recent generation of Pokemon in the dataset is now generation 8. 

TODO: 
-Utilize Pandas, matplotlib or plotly to visualize the newly acquired data

-Use the pokebase API to gather more information for the database such as abilities and moves

Required Tools:

-Python

-SQLAlchemy pip installed
  
-Jupyter Notebook (install from Anaconda Navigator if available)

-PostgreSQL

Process:
1) Clone this repository
2) Create a new Database called "PokemonDB" on any server of your choice
3) Inside that new Database, create a table called "Pokemon"
4) Create a python script called "config"
5) Inside config.py, store your database's username, password, and port insde variable names called "username", "password" and "port" 
6) Activate your Jupyter Notebook from the command line
7) Run the script, "PokemonDataBaseV3", all the way through
8) Verify the data can be queried using the database interface
