# Postman Collection Viewer

View your Postman collection documentation in browser.

<a href="https://www.buymeacoffee.com/gopal" target="_blank"><img src="https://cdn.buymeacoffee.com/buttons/default-orange.png" alt="Buy Me A Coffee" style="height: 51px !important;width: 217px !important;" ></a>

![Screenshot](/pcv.png)

## Project setup

1. `docker compose -f dev/docker-compose.local.yml up -d`
2. `docker exec -it $(docker ps | grep 'postman-collection-viewer' | awk '{print $1}') sh -c 'if [ -x /bin/bash ]; then exec /bin/bash; else exec /bin/sh; fi'`
3. `npm install` (inside the container)

### Compiles and hot-reloads for development

```
npm run serve
```

### Compiles and minifies for production

```
npm run build
```

### Run your tests

```
npm run test
```

### Lints and fixes files

```
npm run lint
```

### Customize configuration

See [Configuration Reference](https://cli.vuejs.org/config/).

### Stay connected

Follow on [Twitter](https://twitter.com/Gopalkildoliya)

<a href="https://www.buymeacoffee.com/gopal" target="_blank"><img src="https://cdn.buymeacoffee.com/buttons/default-orange.png" alt="Buy Me A Coffee" style="height: 51px !important;width: 217px !important;" ></a>
