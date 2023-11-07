
## Connect to container
```sh
docker-compose exec mongodb bash
```
## Connect with mongosh

```sh
mongosh "mongodb://root:root123@localhost:27017/?authMechanism=DEFAULT&tls=false"
mongosh "mongodb+srv://gilcamilo75:39A9aHKvFZQbpVrb@mongodb007.lg8hhnf.mongodb.net/"
```

```sh
show dbs
show collections
```

```sh
use("platzi_store")

db.products.find()
```
