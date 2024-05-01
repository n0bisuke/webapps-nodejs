
- v4.0

```json
{
  "name": "webapps-nodejs",
  "version": "1.0.0",
  "description": "",
  "main": "app.js",
  "scripts": {
    "start": "node node_modules/node-red/red.js",
    "push": "git add . && git commit -m \"資料更新 - $(date '+%Y-%m-%d %H:%M:%S')\" && git push origin node-red"
  },
  "keywords": [],
  "author": "",
  "license": "ISC",
  "dependencies": {
    "express": "^4.19.2",
    "node-red": "^4.0.0-beta.2"
  }
}

```