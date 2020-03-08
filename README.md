# devops-bootcamp-frontend-app

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

## Docker

Para lanzar la aplicación en local, mediante docker, ejecutar:

~~~bash
docker build -t frontend-project .
docker run -p 3000:3000 -v .:  backend-project
~~~