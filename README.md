# Webtech_2_beadando

## Futtatás

# "backend" mappában 'mongod --dbpath="src/db"' parancs
# majd ugyanitt új parancssorból kiadjuk a 

mongoimport --db assignment --collection shutter_colors   --file src/db/testData/testColors.json   --jsonArray

mongoimport --db assignment --collection shutter_mats     --file src/db/testData/testMats.json     --jsonArray

mongoimport --db assignment --collection orders           --file src/db/testData/testOrders.json   --jsonArray

parancsokat.

# Ezután 'npm install' és 'npm start' parancsokkal telepítjük és futtatjuk az appot
