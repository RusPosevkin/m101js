# Final Project (Exam)

### Initialize
1. Install the dependencies.
2. Make sure you have a mongod running version 3.2.x of MongoDB.
```sh
db.version()
```
3. Import the "item" and "cart" collections.
```sh
mongoimport -d mongomart -c item data/items.json
mongoimport -d mongomart -c cart data/cart.json
```
4. Run the application in the mongomart directory.
```sh
node mongomart.js
```