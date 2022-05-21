# Docker
### docker pull mongo
### docker run -d -p 27017:27017 --name shopping-mongo mongo
### docker logs -f shopping-mongo
### docker exec -it shopping-mongo /bin/bash  <interactive terminal>
#### mongo
#### use CatalogDb
#### db.Products.insertMany([{ 'Name':'Asus Laptop','Category':'Computers', 'Summary':'Summary', 'Description':'Description', 'ImageFile':'ImageFile', 'Price':54.93 }, { 'Name':'HP Laptop','Category':'Computers', 'Summary':'Summary', 'Description':'Description', 'ImageFile':'ImageFile', 'Price':88.93 } ])
#### db.Products.find({}).pretty()
#### db.Products.remove({})

#### show databases
#### show collections
#### db.Products.find({}).pretty()
-----------
# .NET Core CLI
### dotnet run
