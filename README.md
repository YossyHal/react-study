## Docker

- https://code.visualstudio.com/docs/devcontainers/create-dev-container

## React

- https://github.com/facebook/create-react-app#create-react-app--

## webpack

- https://webpack.js.org/guides/getting-started/

## Apache HTTP Server

```sh
docker run -dit --rm --name my-apache-app -p 8080:80 -v "$PWD":/usr/local/apache2/htdocs/ httpd:2.4
```