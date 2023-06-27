## A Demo of my skills in MongoDB, Node.js, React.js and Typescript 

I demonstrate my skills with Node.js, React.js, typescript and MongoDB in this repo . 

Building a simple app that uses a React Frontend and a backend Node express Api and routing connecting and retrieving and updating data on local Docker MongoDB instance .
Also included is Webpack for bundling and Prettier and Eslint for formatting and indenting.

For MongoDB I use Docker Desktop with Docker-compose and a Mongodb container from DockerHub 
```yaml
  version: "3"
  services:
    mongo:
      image: mongo
      expose:
        - 27017
      ports:
        - "27017:27017"
```
#### To download the mongo container , first install Docker Desktop and then you can use the up command 

```console
  docker-compose up
```

#### This will download the container and set it up. 

#### Clone the repo and then open a terminal inside the folder and run npm install

```console
  npm install
```

#### When done with that run the webpack bundler : 

```console
  npm run dev:bundler
```
Now run the server

```console
  npm run dev:server
```

#### You can view it in your browser at http://0.0.0.0:8080/
