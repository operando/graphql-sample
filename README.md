## GraphQL

* [Getting Started](http://graphql.org/docs/getting-started/)

## Setup

```
npm install graphql express express-graphql --save
```

or

```
npm install
```

## Run

```
node index.js
```

## Queries

http://localhost:3000/graphql?query={user(id:%221%22){name}}

```
* http://localhost:3000/graphql?query={user(id:"1"){name}}
```

```
{
  user(id: "1") {
    name
  }
}
```

```
{
  "data": {
    "user": {
      "name": "Dan"
    }
  }
}
```

