# Node.js Web App

A simple Node.js web application that prints "Hello World".

## Running with Docker Compose

```bash
docker-compose up
```

The app will be available at http://localhost:3000

## Running with Docker

```bash
docker build -t node-web-app .
docker run -p 3000:3000 node-web-app
```

## Running locally

```bash
npm install
npm start
```

