init package.json with:
$ npm init

then to download this 
$ npm install --save json-server


then edit package.json to tune port and db file 
"start": "json-server -p 3001 -w db.json"
