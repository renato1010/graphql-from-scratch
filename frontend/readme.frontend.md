## Frontend

### Build the front end from scratch

Webpack config: custom `webpack` config file
[./webpack.config.ts](./webpack.config.ts)

### Hybrid Router

Build 4 routes using **Express Server**:

[./src/server.ts](./src/server.ts)

Routes:

- /: home page (React)
- /dashboard: protected route only "god" or "admin" controlled by Express then by React
- /login: React (form)
- /logout: delete session (Express)

### Authorization Middleware:

[./src/lib/middlewares/user.ts](./src/lib/middlewares/user.ts)

### Screenshots

![front end login](./screenshots/login_front_end_Peek%202021-07-10%2017-29.gif)
