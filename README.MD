# The Restaurant Project

The Restaurant Project, for short TRP, is a picking-order system to make the waiter's job easier. This is developped in Angular (Node.Js, HTML & CSS) posted on Firebase servers. 

For the moment, only the login system work.

UPDATE : Design and minor bugs fixed 

## The Goal

At the beginning, it was a school project, but I decided to post it because I think it could help people who develop this kind of system. The system is supposed to take orders from a smartphone and display them on a screen in the kitchen, then confirm the order in the kitchen (call a waiter to take the order).

## Prerequisites
- A Google account liked to Firebase console (in order to make a new project).
- Visual Studio Code
- Node.JS
- Firebase tools

## Installation
 
To setup a live demo you will have to clone this Git with the following command.

```bash
git clone https://github.com/IndySof/The-Restaurant-Project.git
```
Once, you have to set up a project on the Google Console (Firebase) and edit in the [index file](https://github.com/IndySof/The-Restaurant-Project/blob/master/public/index.html), here, change the script by your and apply, it will allow you to use your Firebase's authentification system instead of mine

```html
<script>
  var config = {
    apiKey: "AIzaSyCJZkWAff***************Gt0",
    authDomain: "the-restaurant-project.firebaseapp.com",
    databaseURL: "https://the-restaurant-project.firebaseio.com",
    projectId: "the-restaurant-project",
    storageBucket: "the-restaurant-project.appspot.com",
    messagingSenderId: "779********96",
    appId: "1:77958*****6:web:2db8f*********667a5",
    measurementId: "G-94H*******GC"
  };
  firebase.initializeApp(config);
</script>
```
You are now set, you have to define the project usage (web), and download somes more files :
```bath
npm install
```
then you will be able to try if it work with :
```bath
firebase serve
```
then deploy with
```bath
firebase deploy
```


## Usage

In order to login you have to make an account in the [Google Console](https://console.firebase.google.com/project/your-project-name/authentication/users?hl=en) and try to log on the page.

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.

## License
[MIT](https://choosealicense.com/licenses/mit/)