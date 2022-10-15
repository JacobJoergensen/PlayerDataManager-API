# PlayerDataManager-API
Work in progress...

# DOCS

### DATABASE CONNECT
Connect to your MongoDB collection.

    DbConnect("<Connection String>", "<Database Name>", "<Collection>")
    
### GET PLAYER DATA
Get a specific player data from the database.

    GetPlayerData(player, "<dataset>", "performance")
    
### UPLOAD PLAYER DATA
Upload a specific player data from the server to the database.

    UploadPlayerData(player, "<dataset>", "<value>", "performance")
