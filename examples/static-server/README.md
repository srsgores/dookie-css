# Static server with dookie-css

After cloning the repo, go to *./examples/static-server* folder:

```bash
cd examples/static-server
```
install dependecies:

```bash
npm install
```

and start application:

```bash
node server.js
```

it's recommended to use [nodemon](https://github.com/remy/nodemon) if you do not want to reload server after every change:

```bash
nodemon --legacy-watch --watch public -e styl server.js
```

go to to ``localhost:8081`` in your browser, you will see dookie landing page with tiny css clouds :)