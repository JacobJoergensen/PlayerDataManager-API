# PlayerDataManager-API
Work in progress... (long way..)

# DOCS

### DATABASE CONNECT
Connect to your MongoDB collection.

    DbConnect("<Connection String>", "<Database Name>", "<Collection>")
    
### GET PLAYER DATA
Get a specific player data from the database.

    GetPlayerData(player, "<dataset>", true)
    
### UPLOAD PLAYER DATA
Upload a specific player data from the server to the database.

    UploadPlayerData(player, "<dataset>", "<value>", true)
