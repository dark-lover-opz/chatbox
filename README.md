# My Catbox Uploader

Simple file upload API on Render (local disk storage).

## Local Run
npm install
npm start

## Test
curl -X POST http://localhost:3000/api/upload -F "file=@image.jpg"

## Deploy
Push to GitHub, connect on render.com (Web Service, Node env).