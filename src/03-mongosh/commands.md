# Connect to container

'''sh
docker-compose.yml exec mongodb bash
'''

# Connect with mongosh

'''sh
mongosh "mongodb://root:gio12345@localhost:27017/?authMechanism=DEFAULT&tls=false"
mongosh "mongodb+srv://giovannydelacruz10:gio12345@mongodb101.zsx6uin.mongodb.net/test"
'''

'''sh
show dbs
show collections
'''

'''sh
use("platzi_store")
db.products.find()
'''

'''sh
.exit
'''

'''sh
exit
'''

'''sh
docker stop d1870d60dae3
'''