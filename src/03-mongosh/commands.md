## Connect to container

´´´sh
docker-compose exec mongodb bash
´´´

## Connect using mongosh
´´´sh
mongosh ""
´´´

´´´sh
show dbs
show collections


´´´sh
use ("prueba_tienda")
db.products.find()
´´´