# REST API UserService

1. **GET** /users -- list of users -- 200, 404, 500
2. **GET** /users/:id -- user by id -- 200, 404, 500
3. **POST** /users/:id -- create user -- 204, 4xx, Header Location: url
4. **PUT** /users/:id -- full user update -- 204/200, 404, 400, 500
5. **PATCH** /users/:id -- partially user update -- 204/200, 404, 400, 500
6. **DELETE** /users/:id -- delete user by id -- 204, 404, 400
