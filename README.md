# DevConnector

[Click here for live demo](https://luddite.herokuapp.com/)

> Social network for developers

This is a MERN stack application from the "MERN Stack Front To Back" course on [Udemy](https://www.udemy.com/course/mern-stack-front-to-back/). It is a small social network app that includes authentication, profiles and forum posts.

# Quick Start 🚀

### Add a default.json file in config folder with the following

```
{
  "mongoURI": "<your_mongoDB_Atlas_uri_with_credentials>",
  "jwtSecret": "secret",
  "githubToken": "<yoursecrectaccesstoken>"
}
```

### Install server dependencies

```bash
yarn install
```

### Install client dependencies

```bash
cd client
yarn install
```

### Run both Express & React from root

```bash
yarn dev
```

### Build for production

```bash
cd client
yarn build
```
