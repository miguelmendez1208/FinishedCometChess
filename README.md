## Running the frontend (skip this part just use the docker container image)
```
npm install
npm run serve
```
#build the frontend image
```
docker build -t front .
docker run -p 8080:8080 front
```
### Running the server (skip this part just use the docker container image)
```
cd server
npm install
npm start
```
#build the backend image
```
cd server
docker build -t back .
docker run -p 3000:3000 back
```
