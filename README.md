# pro-kriyam

A easy to use project management system built using React, and under the hood it uses Redmine

# setup

rename .env.example to .env ant update API endpoints

# build & deploy

use docker to build and deploy

```sh
docker-compose --env-file .env.production up --build
```

# snackbar

You can pass title as header of the snackbar

```js
enqueueSnackbar("This is a message!", { variant: "success", title: "This is a title" })
```
