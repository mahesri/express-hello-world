# Cyclic - Age Calculator 


- Static file hosting Which will provide services in the form of applications that can calculate a person's age. 

### Try the service -> [![Aplikasi Mengetahui Umur](https://deploy.cyclic.app/button.svg)](https://erin-frightened-eagle.cyclic.cloud/)


This is a basic starter Expressjs app with:

- Static file hosting Which will provide services in the form of applications that can calculate a person's age. 
- Logging Middleware
- Catch-all handler that echoes request info



## Local Quick Start

- Clone to your local
- Install dependencies `npm install`
- Run locally `npm serve`
- Make requests
  - Browser: `http://localhost:3000/some/path?q=query+one&q=second+query&single=value`
  - Command line: `curl -i -XGET "http://localhost:3000/cmd/line-curl"`

## Deploy in under 10 seconds

[![Deploy to Cyclic](https://deploy.cyclic.app/button.svg)](https://deploy.cyclic.app/)
- Sets up instant continuous deployment on `git push`
- Realtime backend logs and API request monitoring

### Cyclic Runtime

- Cyclic hosts your app on serverless infrastructure. That means there is no guarantee of memory or file system persistence between requests.
- The runtime expects a nodejs entry point defined as:
  - package.json "main" field defines the entry point file (if missing uses index.js)
  - Entry point starts a server on `process.env.PORT`


