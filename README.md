
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

###  build the Docker image of our Vue.js app:
```
docker build -t vuejs-cookbook/dockerize-vuejs-app .
```

###  run the Docker image of our Vue.js app:
```
docker run -it -p 8080:80 --rm --name dockerize-vuejs-app-1 vuejs-cookbook/dockerize-vuejs-app
```

### Customize configuration
See [Configuration Reference](https://cli.vuejs.org/config/).
