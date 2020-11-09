# fastify-jwt-skeleton
![Version](https://img.shields.io/github/package-json/v/aalfiann/fastify-jwt-skeleton)
[![Build Status](https://travis-ci.com/aalfiann/fastify-jwt-skeleton.svg?branch=master)](https://travis-ci.com/aalfiann/fastify-jwt-skeleton)
[![Coverage Status](https://coveralls.io/repos/github/aalfiann/fastify-jwt-skeleton/badge.svg?branch=master)](https://coveralls.io/github/aalfiann/fastify-jwt-skeleton?branch=master)
[![Known Vulnerabilities](https://snyk.io//test/github/aalfiann/fastify-jwt-skeleton/badge.svg?targetFile=package.json)](https://snyk.io//test/github/aalfiann/fastify-jwt-skeleton?targetFile=package.json)
[![dependencies Status](https://david-dm.org/aalfiann/fastify-jwt-skeleton/status.svg)](https://david-dm.org/aalfiann/fastify-jwt-skeleton)
[![JavaScript Style Guide](https://img.shields.io/badge/code_style-standard-brightgreen.svg)](https://standardjs.com)
![License](https://img.shields.io/github/license/aalfiann/fastify-jwt-skeleton)  
Just simple Fastify with JWT skeleton.

### Features
- Auto cache and can be configured
- Routes with schema validation
- JWT Authentication
- Error handler for 4xx and 5xx
- Asynchronous designed
- HTML auto minifed

### Specs
- Fastify v3
- Mongoose 5
- ETA Template Engine

### Requirement
- NodeJS v10
- MongoDB v4

### Usage

1. Download this source code.
2. Extact and go to current directory then run `npm install`
3. Edit the `config.js`
4. Run `node server.js`
5. Done.

Then open your browser and go to 
```
- http://localhost:3000
- http://localhost:3000/api/routes
```

For API, MongoDB and Authentication Test  
We provided `postman_collection.json` files, just import it to your postman.

### Unit test
If you want to play unit test
```
npm test
```

### Note
- If you want to regenerate private and public key, go to here >> [http://travistidwell.com/jsencrypt/demo](http://travistidwell.com/jsencrypt/demo/).
- If you want to validate the JWT Token, go to here >> [https://jwt.io](https://jwt.io/)
