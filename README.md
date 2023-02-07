<p align="center">
  <a href="https://pinia.vuejs.org" target="_blank" rel="noopener noreferrer">
    <img height="60" src="https://user-images.githubusercontent.com/11756007/216806071-06877e52-b089-448f-8d3d-e79d1e99958b.svg" alt="Pinia logo">
  </a>
</p>
<br/>
<p align="center">
<a href="https://www.npmjs.com/package/imagify-api-client-node" target="__blank"><img alt="NPM Downloads" src="https://img.shields.io/github/downloads/magictm/imagify-api-client-node/total?flat&colorA=002438&colorB=28CF8D"></a>
<a href="https://github.com/magictm/imagify-api-client-node" target="__blank"><img alt="GitHub stars" src="https://img.shields.io/github/stars/magictm/imagify-api-client-node?flat&colorA=002438&colorB=28CF8D"></a>
</p>
<br/>

# Imagify API Client for Node.js

A lightweight and easy-to-use library for accessing the Imagify API from Node.js applications. Written in JavaScript, this library provides a simple and straightforward interface for integrating with the Imagify API and optimizing your images.

Imagify API Docs: https://imagify.io/docs/api/

## ⚠ Important Notice: This project is in the early stages of development and is not yet ready for use in real-world settings. 
While we are working hard to make it the best it can be, there may still be some issues that need to be addressed. For this reason, we strongly advise against using this project in a production environment until it has been fully tested and deemed ready for use. Thank you for your understanding.

## 🔥 Features
- Simple, intuitive API interface 💻
- Lightweight and efficient 🚀
- Full support for all Imagify API features 💯
## 💾 Installation
To install the Imagify API Client for Node.js, simply run the following command in your terminal:

```js
npm install imagify-api-client-node
```
## 📈 Usage
Using the library is easy and straightforward. Simply require the package in your Node.js script and call the appropriate methods to interact with the Imagify API.

```js
const imagify = require('imagify-api-client-node');

// Your Imagify API Key
const apiKey = 'YOUR_API_KEY';

// Optimize an image
imagify.optimizeImage(apiKey, 'path/to/image.jpg')
  .then(data => {
    console.log(data);
  })
  .catch(error => {
    console.error(error);
  });
```
For more information on how to use the library and access the full range of features offered by the Imagify API, please refer to the documentation.

## 🛠️ Development
This library is open source and actively maintained. If you would like to contribute to the development of the library, please start by discussing the changes you would like to make in a new issue. This will ensure that your changes are in line with the goals and vision of the project.
## 💰 Support
If you use and enjoy this library, please consider supporting the project by making a donation or sharing it on social media. Your support helps us to continue developing and maintaining this library for the benefit of the community.

[Support the project](https://www.paypal.com/paypalme/merlinArtist)!
## 📄 License
This library is licensed under the MIT license. For more information, please see the [LICENSE](LICENSE) file.
