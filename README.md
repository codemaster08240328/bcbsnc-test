# bcbsnc-test

This is the global wrapper which manages `client`, `server` and `web-components` in one repository. 

> Node.js version 14.x is recommended.

## How to run the application.
1. Build and Link web components
```bash
$ cd web-components
$ npm i
$ npm run build
$ npm link
```

2. Build and run backend application
```bash
$ cd server
$ npm i
$ npm start
```

3. Build and run frontend application
```bash
$ cd client
$ npm i
$ npm link web-components
$ npm start
```

## For more specific instruction
- web-components: [here](https://github.com/codemaster08240328/web-components#readme)
- server: [here](https://github.com/codemaster08240328/server#readme)
- client: [here](https://github.com/codemaster08240328/client#readme)