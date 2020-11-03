# PokeBase

This is a personal project for SQLAlchemy Practice. By using a SQLAlchemy-derived engine, I connected my Jupyter Notebook kernel to the database that houses the most updated
dataset I have on Pokemon. The dataset goes up to order #722, which has about 800 rows of pokemon data. 

The last entry is Volcanion, which is a generation 6 pokemon. The current generation as of this repository's creation is generation 8. Pokemon from the Sun, Moon, Shield & 
Sword games and their information are not included. 

TODO: 
-Acquire the missing Pokemon information from Pokemon Sun, Moon, Shield & Sword
-Incorporate that data into a dataframe for pre-processing and cleaning
-Bulk insert the data into the SQL database

Required Tools:
-Python
  -SQLAlchemy pip installed
 -Jupyter Notebook (install from Anaconda Navigator if available)
-PostgreSQL or any other SQL-based database

Process:
1) Clone this repository
2) Create a new Database called "Pokemon" on any server and in the SQL flavor of your choice 
3) Inside that new Database, create a table called "PokemonDB"
4) Create a python script called "config"
5) Inside config.py, store your database's username, password, and port insde variable names called "username", "password" and "port" 
6) Activate your Jupyter Notebook from the command line
7) Run the script, "PokemonDataBaseV3", all the way through
8) Verify the data can be queried using the database interface
