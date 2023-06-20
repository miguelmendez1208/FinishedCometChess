## Running the frontend

```
npm install
npm run serve
```
#build the frontend image
```
docker build -t front .
docker run -p 8080:8080 front
```
### Running the server
```
cd server
npm install
npm start
```
#build the backend image
```
docker build -t back .
docker run -p 3000:3000 back
```
