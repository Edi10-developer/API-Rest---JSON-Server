# Employees - API Rest

> This is an simple API of employees build with Node.js.
  It is reusable and easily customizable through POSTMAN

## View:

 **JSON**

![Image](.(employees-server/img/example.png)


## Getting started

Install JSON Server 

```
npm install -g json-server
```

Create a `db.json` file with some data

```json
{
  "posts": [
    { "id": 1, "title": "json-server", "author": "typicode" }
  ],
  "comments": [
    { "id": 1, "body": "some comment", "postId": 1 }
  ],
  "profile": { "name": "typicode" }
}
```

Start JSON Server

```bash
json-server --watch db.json
```

Now if you go to [http://localhost:3000/posts/1](http://localhost:3000/posts/1), you'll get


```json
{ "id": 1, "title": "json-server", "author": "typicode" }
```

Also when doing requests, it's good to know that:

- If you make POST, PUT, PATCH or DELETE requests, changes will be automatically and safely saved to `db.json` using [POSTMAN](https://www.postman.com/).
- Your request body JSON should be object enclosed, just like the GET output. (for example `{"name": "Foobar"}`)
- Id values are not mutable. Any `id` value in the body of your PUT or PATCH request will be ignored. Only a value set in a POST request will be respected, but only if not already taken.
- A POST, PUT or PATCH request should include a `Content-Type: application/json` header to use the JSON in the request body. Otherwise it will return a 2XX status code, but without changes being made to the data. 


## Built With

- JavaScript
- NodeJS
- [JSON Server](https://www.npmjs.com/package/json-server)
- [Faker JS](https://www.npmjs.com/package/faker)


## Author

👤 **Author**
- GitHub: [@Edi10-developer](https://github.com/Edi10-developer)
- LinkedIn: [LinkedIn](https://www.linkedin.com/in/edi-selimi-856671173/?locale=en_US)
- Portfolio: [www.ediselimi.com](https://ediselimi.com/)


## Show your support

Contributions, issues, and feature requests are welcome!
Give a ⭐️ if you like this project!

## Acknowledgments

- Hat tip to anyone whose code was used
- Inspiration
- etc

