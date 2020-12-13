# Face-Rekognition-React
React + Postgre SQL + Database + Node.js + Express.js + JavaScript

<div align='center'><img src="./pics/front.jpg"/></div>

# <div align='center'>💡 Smart Brain App</div>

<div align='center'>
<p>
    <img src="https://www.herokucdn.com/deploy/button.svg"/><p>
    <a href="https://face-rekognitionz.herokuapp.com/"><img src="https://img.shields.io/website?down_color=grey&down_message=offline&style=flat-square&up_color=brightgreen&up_message=online&url=https%3A%2F%2Fsmart-brain-claire.herokuapp.com%2F"/></a>
    <img src="https://img.shields.io/npm/v/react?label=react&style=flat-square&color=9cf"/>

</p>
<p>
A face recognition app that uses the Clarifai API to detect and locate a human face in the picture.

A full-fledged app with user registration and login system. Frontend built with React.js, backend server and APIs with Node.js & Express.js, and PostgresSQL as database to keep track of how many entries a user has made. Deployed on Heroku.

</p>
<p><strong><a href="https://face-rekognitionz.herokuapp.com/">
Click here for Live demo</a></strong>
</p>
<img src="./pics/taylor1.jpg"/>
<img src="./pics/girl.jpg"/>
</div>

## 📕 How to Use the App

- Sign Up / Log In
- Input an image url and click detect button
- The app detects the face in the picture and highlight it with a blue bounding box.

## ✨ Features

- A complete user registration system
- Modern & Responsive UI, particle background effects created with Particle.js library
- Separate frontend and backend, easy modifications

## ⚙️ Installation

From your command line, first clone the project:

### Clone this repository

```zsh
$ https://github.com/taroserigano/Face-Rekognition-React.git

Go into the repository
$ cd smart-brain-app

# Remove current origin repository
$ git remote remove origin
```

### Install the dependencies

```zsh
# Install dependencies
$ npm install

# Start dev development server
$ npm run dev
```

After installation, open [http://localhost:3000](http://localhost:3000), or if you are running both frontend and the backend, you can run it on [http://localhost:3001](http://localhost:3000) to view it in the browser.



### New Build

```zsh
$ npm run start
```

### Deploy to Heroku

Please Refer to the [official document](https://devcenter.heroku.com/articles/git#tracking-your-app-in-git)

## 🤟 Languages

<div>
<img src="https://img.shields.io/badge/javascript%20-%23323330.svg?&style=for-the-badge&logo=javascript&logoColor=%23F7DF1E"/>
<img src="https://img.shields.io/badge/react%20-%2320232a.svg?&style=for-the-badge&logo=react&logoColor=%2361DAFB"/>
<img src="https://img.shields.io/badge/node.js%20-%2343853D.svg?&style=for-the-badge&logo=node.js&logoColor=white"/>
<img src="https://img.shields.io/badge/express.js%20-%23404d59.svg?&style=for-the-badge"/>
<img src="https://img.shields.io/badge/postgres-%23316192.svg?&style=for-the-badge&logo=postgresql&logoColor=white"/>
<img src="https://img.shields.io/badge/html5%20-%23E34F26.svg?&style=for-the-badge&logo=html5&logoColor=white"/>
<img src="https://img.shields.io/badge/css3%20-%231572B6.svg?&style=for-the-badge&logo=css3&logoColor=white"/>
</div>

## 🛠️ Technologies

### APIs

- [Clarifai API](https://www.clarifai.com/models/face-detection) - Predict api to tell what is in your images, videos or text. Capture data about the physical world through images.

- [Smart Brain API](https://github.com/clairepeng0808/smart-brain-api) - Smart Brain API endpoints.

### NPM Packages

- [Material UI](https://material-ui.com/getting-started/installation/) - React UI framework
- [particles.js](https://vincentgarreau.com/particles.js/) - Lightweight JS library for creating particles.
- [serve](https://www.npmjs.com/package/serve) - for serving a single page app or static files
