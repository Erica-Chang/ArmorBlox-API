# ArmorBlox-API
API Tests for Armorblox

## Install
Install Newman 

```bash 
npm install -g newman
``` 

Install Newman HTML reporter
```bash
npm install -g newman-reporter-html
```

## Running Postman API Collection in the Terminal 

```bash
newman run MusicDemons.postman_collection.json -e MusicDemons.postman_environment.json
```

## Running Postman API with HTML Report 
```bash
newman run MusicDemons.postman_collection.json -e MusicDemons.postman_environment.json -r html
```
A New html report of the test will appear in ./newman
