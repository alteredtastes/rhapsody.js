# jook.me (rhapsody.js example app)

### Getting Started

First add the following callback url to the application setting on [developer.rhapsody.com](https://developer.rhapsody.com)

```
http://localhost:2000/authorize
```

This application requires node.js. If you have not previously installed it please follow the instructions at [nodejs.org](https://nodejs.org).

### Running the application

In `server.js` replace the `apiKey` and `apiSecret` variable placeholder values with your application's credentials. In `client.html` replace the `API_KEY` variable placeholder value with your application's credentials. Assuming you have already installed npm run the following commands in from the inside the example app directory.

```
npm install
node server.js
```

That's it! Once the server application is running you can navigate in the browser to [localhost:2000](http://localhost:2000). 