## Docker

- https://code.visualstudio.com/docs/devcontainers/create-dev-container

## React

- https://github.com/facebook/create-react-app#create-react-app--

### React Quick Overview

```sh
yarn create react-app my-app
```

## Apache HTTP Server

```sh
yarn build
docker run -it --rm --name my-apache-app -p 8080:80 -v "${PWD}/build":/usr/local/apache2/htdocs/ httpd:2.4
```
