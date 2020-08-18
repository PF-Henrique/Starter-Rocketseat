<h1 align="center">
    <img alt="proffy-landing" src="https://github.com/PF-Henrique/Starter-Rocketseat/blob/master/.github/starter-logo.svg" />
</h1>

<h2 align="center">
     ProductHunt API
</h2>

<h4 align="center">
     Siga os passos descritos nos README.md de cada diretorio
</h4>

<p align="center">
  <a href="https://github.com/PF-Henrique/Starter-Rocketseat/tree/master/web">💻 Acesse o Front-end</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="https://github.com/PF-Henrique/Starter-Rocketseat/tree/master/api">🖥 Acesse o Back-end</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="https://github.com/PF-Henrique/Starter-Rocketseat/tree/master/mobile">📱 Acesse o Mobile</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
</p>
<br>

# 🚀 Welcome to huntapi

Backend developed in the **[Starter / NodeJS Course](https://rocketseat.com.br/starter)** by **[Rocketseat](https://rocketseat.com.br/)**.

It consists of an API connected to a Mongo database performing basic CRUD operations to handle storage of digital products.

## 🧰 Prerequisites
Make sure you have installed all of the following prerequisites on your machine:
* **[Git](https://git-scm.com/downloads)**;
* **[Node.js](https://nodejs.org/en/download/)** with npm package manager;
* **[Docker](https://docs.docker.com/engine/install/) OR [MongoDB](http://www.mongodb.org/downloads)** running on the default port (27017).

## 🔧 Install
### With Docker
```sh
$ docker pull mongo
$ git clone https://github.com/rhenangarcia/huntapi
$ cd huntapi/
$ npm install

### With MongoDB
```sh
$ git clone https://github.com/rhenangarcia/huntapi
$ cd huntapi/
$ npm install
```

## ⚙️ Usage
### With Docker
```sh
$ docker run --name mongodb -p 27017:27017 -d mongo
$ node server.js
```
* Access [http://localhost:3001/api/products](http://localhost:3001/api/products) on your browser.

### With MongoDB
```sh
$ node server.js
```
* Access [http://localhost:3001/api/products](http://localhost:3001/api/products) on your browser.

## 📚 API documentation
### *Product* data model
```
{
  "title": String,
  "description": String,
  "url": String,
  "createdAt": Date
}
```

### HTTP methods
* **`GET` /api/products&page=*PAGE_NUMBER***
  * Show detailed products list using pagination query.
* **`GET` /api/products/id**
  * Show product details by ID.
* **`POST` /api/products**
  * Create product sending a JSON body.
* **`PUT` /api/products/id**
  * Update product by ID sending a JSON body.
* **`DELETE` /api/products/id**
  * Delete product by ID.
  
### Production Environment
* [ReactJS deployment documentation](https://create-react-app.dev/docs/deployment/#github-pages)
* [GitHub Pages workaround](https://github.com/rafgraph/spa-github-pages#usage-instructions)

## 👤 Author
* **GitHub: [@PF-Henrique](https://github.com/PF-Henrique)**
* **LinkedIn: [@PedroFerreira](https://www.linkedin.com/in/pedro-ferreira-148503b8/)**

## 🤝 Contributing
There are many forms to contribute with the project, first of all you can give this github repo a Star.

If you want do help with the code follow the steps bellow

```ts
# Fork using GitHub official command line
# If you don't have the GitHub CLI, use the web site to do that.
$ gh repo fork PF-Henrique/Be-The-Hero

# Clone your fork
$ git clone {your-fork-url}
$ cd proffy

# Create a branch with your feature
$ git checkout -b {branch-name}

# Make the commit with your changes
$ git commit -m 'Feat: {feature-name}'

# Send the code to your remote branch
$ git push origin {branch-name}
```

Then send a Pull Request that will be analyzed and approved if it helps with the project

---
## 🐛 Issues

Feel free to **file a new issue** with a respective title and description on the the [ProductHunt](https://github.com/PF-Henrique/Starter-Rocketseat/issues) repository. If you already found a solution to your problem, **i would love to review your pull request**!


## 💓 Support me
Give a ⭐️ if this project helped you!

## 📝 License
#### This project is [MIT](LICENSE) licensed. 
---

## ✨ Me

<a href="https:https://github.com/PF-Henrique/">
  <img src="https://avatars1.githubusercontent.com/u/48561196?s=460&u=5b39cdc8c6d447868ca0caac900f1ee7a1793962&v=4" width= "50px;" height= "50px;" alt="Avatar"/>
  <br />
 <sub>
  <b>
    Pedro Ferreira
  </b>
</sub>
</a> 
<a href="<a href="https:https://github.com/PF-Henrique/" title="ProductHunt">🚀👩‍🚀</a>
<br />

Made with 💙 by Pedro Ferreira 👋 [Talk to me!](https://www.linkedin.com/in/pedro-ferreira-148503b8/) :octocat:
