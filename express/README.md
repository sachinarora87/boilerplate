# Starter template for Node.js/ Express

The bundle contains REST server sample with asynchronous controller actions written in MVC style

## Available Automation Commands
- `npm start` - start server


## package.json

- `express` - [Express.js, web framework for Node.js](https://expressjs.com/)
- `body-parser` - [Node.js body parsing middleware](https://www.npmjs.com/package/body-parser)
- `minimist` - [parse argument options](https://www.npmjs.com/package/minimist)
- `debug` - [ debugging utility](https://www.npmjs.com/package/debug)

## Implemented methods

```
curl -X GET http://127.0.0.1:9002/news/101
```
Possible response: `{"content":"Content of new entry 101"}`


```
curl -X POST http://127.0.0.1:9002/news \
  -H 'content-type: multipart/form-data' \
  -F 'title=some title' \
  -F 'body=some body'
```

Possible response: `{"message":"News entry with id 69 added"}`