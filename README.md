## Installation Guide

### Requirements
- [Nodejs](https://nodejs.org/en/download)
- [Mongodb](https://www.mongodb.com/docs/manual/administration/install-community/)

Both should be installed and make sure mongodb is running.

```shell
git clone https://github.com/jahnavi02/depo24
cd chat-app-react-nodejs
```
Now rename env files from .env.example to .env
```shell
cd frontend
mv .env.example .env
cd ..
cd backend
mv .env.example .env
cd ..
```

Now install the dependencies
```shell
cd backend
yarn
cd ..
cd frontend
yarn
```
We are almost done, Now just start the development server.

For Frontend.
```shell
cd frontend
npm start
```
For Backend.

Open another terminal in folder, Also make sure mongodb is running in background.
```shell
cd backend
npm start
```

Done! Now open localhost:3000 in your browser.
