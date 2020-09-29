 ---
 ### To create new Project in reactJs 
```javascript 
    * npx create-react-app appName
```
 [More Details](https://github.com/facebook/create-react-app)

---
 ### For starting the project open the terminal or cmd and go to the directory where you created that project
```javascript 
    * cd appName
    * npm start
```

---
 ### After give the `npm start` command if the project is not starting or it shows the `unhandled error` then `delete your node-modules files and pacakges.json.lock file`.After that give the following command 
```javascript 
    * npm install
    * npm start
```

---
 ### For adding React Bootstrap in your project 
```javascript 
    * npm install --save bootstrap
     Then import this on your src/index.js file,
    * import 'bootstrap/dist/css/bootstrap.css';
```
 [More Details](https://create-react-app.dev/docs/adding-bootstrap/)
###### Or,
```javascript 
    * npm install react-bootstrap bootstrap
```
###### Or,
### You can use the CDN link of CSS. If you are using CDN link then you can use bootstrap as like simply use with html.
```javascript 
    <link
  rel="stylesheet"
  href="https://maxcdn.bootstrapcdn.com/bootstrap/4.5.0/css/bootstrap.min.css"
  integrity="sha384-9aIt2nRpC12Uk9gS9baDl411NQApFmC26EwAOH8WgZl5MYYxFfc+NcPb1dKGj7Sk"
  crossorigin="anonymous"
/>
```
 [More Details](https://react-bootstrap.github.io/getting-started/introduction/)


---
### To add Material-UI in your React Project 
```javascript 
    * npm install @material-ui/core
    * npm install @material-ui/icons
```
 [More Details](https://material-ui.com/getting-started/installation/)

---


### For using FontAwesome in your project 
```javascript 
    * npm i --save @fortawesome/fontawesome-svg-core
      npm install --save @fortawesome/free-solid-svg-icons
      npm install --save @fortawesome/react-fontawesome
```
```javascript 
        // Light:
        <FontAwesomeIcon icon={["fal", "coffee"]} />
        // Regular:
        <FontAwesomeIcon icon={["far", "coffee"]} />
        // Solid
        <FontAwesomeIcon icon={["fas", "coffee"]} />
        // ...or, omit as FontAwesome defaults to solid, so no need to prefix:
        <FontAwesomeIcon icon="coffee" />
        // Brand:
        <FontAwesomeIcon icon={["fab", "github"]} />
```
 [More Details](https://fontawesome.com/how-to-use/on-the-web/using-with/react)

---
### For using charts in your react projects 
```javascript 
    * npm install recharts
```
 [More Details](https://recharts.org/en-US/guide/installation)

---
### For using react `axios` to sent the api request 
```javascript 
    * npm install react-axios
    * npm install axios
    * npm install react
    * npm install prop-types
```
 [More Details](https://www.npmjs.com/package/react-axios)

---

### For Using React Router Dom in your React Project 

```javascript 
    * npm install react-router-dom
```
 [More Details](https://reactrouter.com/web/guides/quick-start)

---

### For using React Redux in your project 

```javascript 
    * npm install react-redux
```
 [Redux for Begineers](https://redux.js.org/basics/basic-tutorial)
 [More Details](https://react-redux.js.org/introduction/quick-start)



---
### To add firebase on your project 
```javascript 
    * npm install --save firebase
       // Firebase App (the core Firebase SDK) is always required and must be listed first
        import * as firebase from "firebase/app";

        // If you enabled Analytics in your project, add the Firebase SDK for Analytics
        import "firebase/analytics";

        // Add the Firebase products that you want to use
        import "firebase/auth";
        import "firebase/firestore";
```
 [More Details](https://firebase.google.com/docs/web/setup?authuser=0)

---

