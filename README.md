# Installation steps:
```sh
dex neo_frontend yarn install
```

## Development Mode
```sh
dex neo_frontend yarn run start
# or !
dex neo_frontend yarn start
```

Wait for the project to compile, you'll know it's done when you see:
```
Compiled successfully!

You can now view app in the browser.

  Local:            http://localhost:3000
  On Your Network:  http://172.18.0.14:3000

Note that the development build is not optimized.
To create a production build, use yarn build.
```

In development mode, you will automatically watch files and recompile them as necessary.
As the compiled message says, open [http://localhost:3000](http://localhost:3000) in your browser.

## Production Mode
This mode is useful when you plan on just using the application, as opposed to working on it.

```sh
dex neo_frontend yarn run build
# or !
dex neo_frontend yarn build
```

Wait for the project to compile, you'll know it's done when you see:
```
