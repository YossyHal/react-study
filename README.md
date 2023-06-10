## Docker

- https://code.visualstudio.com/docs/devcontainers/create-dev-container

## React

- https://github.com/facebook/create-react-app#create-react-app--

### React Quick Overview

```sh
npx create-react-app my-app
cd my-app
npm start
```

### React deploy to GitHub Pages

- https://docs.github.com/ja/pages/getting-started-with-github-pages/about-github-pages
- https://docs.github.com/ja/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site

```sh
cd my-app
npm run build
git subtree push --prefix build/ origin github-pages
```
