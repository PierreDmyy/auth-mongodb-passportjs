# AUTH-MONGO
Simple authentication with node JS and mongodb

## Installation

Install modules
```bash
npm i
```

## Usage
In `config/keys.js`
replace : 
```javascript
module.exports = {
    MongoURI: process.env.MongoURI
}
```
by : 
```javascript
module.exports = {
    MongoURI: <YouClusterMongoDBUri>
}
```
## Run
```bash
npm run dev
```
##Demo
[DEMO](https://authmongo.herokuapp.com/users/login)
## License
[MIT](https://github.com/PierreDmyy/auth-mongoDB/blob/master/LICENSE)
