# Webtech_2_beadando

## Futtatás

# "backend/src" mappában 'mongod --dbpath="db"' parancs
# majd ugyanitt új parancssorból kiadjuk a 

mongoimport --db assignment --collection shutter_colors   --file testData/testColors.json   --jsonArray
mongoimport --db assignment --collection shutter_mats     --file testData/testMats.json     --jsonArray
mongoimport --db assignment --collection orders           --file testData/testOrders.json   --jsonArray

parancsokat.

# Ezután 'npm install' és 'npm start' parancsokkal telepítjük és futtatjuk az appot
