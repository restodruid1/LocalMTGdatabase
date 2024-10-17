# LocalMTGdatabase
![MTGdatabase](https://github.com/restodruid1/LocalMTGdatabase/blob/main/MTGgithub.PNG) ![MTGdatabase](https://github.com/restodruid1/LocalMTGdatabase/blob/main/MTGgithub2.PNG) 

# Description
Create your own local MTG card database with the ability to access the cards from any local computer.  
In the screenshots above, the card Vampiric Tutor is searched for with autofill capabilities and added
to the local database. Then the card is searched for on the database server, returning the results.  
Simple application using CRUD and basic client/server connection.  
This application connects to the Scryfall API and gives access to their card database.  

# Installation
1. Download all three Python files
2. Manually add your IP address to the host variable in both client/server files
3. Run MTG_API_Database.py to populate your database
4. Run pythonServer.py
5. Run pythonClient.py

# Features
Add, delete, or search your database for a specific card.  
The add feature has autofill capabilities.  
Scryfall API

# Roadmap
1. Ability to read all from database
2. Incorporate other data besides card name and quantity
3. Access the server when not on same network
