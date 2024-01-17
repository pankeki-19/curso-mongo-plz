## Connect to container

´´´sh
docker-compose exec mongodb bash
´´´

## Connect using mongosh
´´´sh
mongosh "mongodb://root:root123@localhost:27017/?authMechanism=DEFAULT"
mongosh "mongodb+srv://mumuminad:u7OysmzOvII9Edtk@mongodb101.n7w5gp4.mongodb.net/"
´´´

´´´sh
show dbs
show collections


´´´sh
use ("prueba_tienda")
db.products.find()
´´´

## Disconnect
´´´sh
.exit
´´´
