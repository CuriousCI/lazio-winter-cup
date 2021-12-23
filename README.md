# Lazio Winter Cup
Website for Lazio Winter Cup volley tournament 2021

## How to collaborate
First of all, you have to make a [GitHub](https://github.com/) account,
then **fork** [this repository](https://github.com/CuriousCI/lazio-winter-cup), make your changes, then, make a pull-request to send 
changes for a review.
## Setup
First, make sure you have installed [nodejs](https://nodejs.dev/), then
run the following commands to locally build and run the project:
```bash
npm install
npm run dev
```
Then, open localhost:5000 on your browser and enjoy!

## Publication
The official code will be published to 
[Firebase](https://firebase.google.com/) 
by the owner of the project 
[*(Ionut Cicio)*](https://github.com/CuriousCI). If you want to test 
the webapp yourself, you should login to 
[Firebase](https://firebase.google.com/), create a new project, and 
follow the instructions in the "hosting" section of your project's 
dashboard. 

The commands to publish the website are the following:

```bash
npm install -g firebase-tools
firebase login
firebase init
npm install firebase
```

You should also create a **firebase.config.js** file for your 
firebase project's configuration.
