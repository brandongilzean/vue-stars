# ratings

A app that shows examples of ratings for an app and always puts it in a docker container.


# Files contained

- Dockerfile for buiding with nginx


# Build with docker

docker build -t vuejs-cookbook/dockerize-vuejs-app .


## Run in Docker container

docker run -it -p 8080:80 --rm --name dockerize-vuejs-app-1 vuejs-cookbook/dockerize-vuejs-app


## Project setup
```
npm install
```

### Compiles and hot-reloads for development
```
npm run serve
```

### Compiles and minifies for production
```
npm run build
```

### Lints and fixes files
```
npm run lint
```

### Customize configuration
See [Configuration Reference](https://cli.vuejs.org/config/).
