# unitn-tronchet

Site where there are simulations of the theoric part of unitn exam "linguaggi di programmazione - mod 1".

__link to the site:__ [https://unitn-tronchet.herokuapp.com](https://unitn-tronchet.herokuapp.com)

## Project purpose:

The UniTN's "Programming Languages" exam's theoric part consists in some code examples in wich the student must find errors or write the output whether there are none and some true or false questions. On the professor's site there are only few examples and the repository with all the old exams has not all the solutions. This is why I made this site, where not only can students see the old exams with the solution, but can enjoy a real simulation, with time and final score.

## How to use it:

## How was it made:

The site's frontend has been made with **Vue.js** and **Typescript**, in particular by using the **Vuetify.js** ui framework. **vue-router** has been used for the routing, **Vuex** as the data store and a **service-worker** was added to make the site a **PWA**. With a **Firebase Cloud Messaging"**, if the user agrees when the site gets entered for the first time, I can send **Push Notifications** when for instance I add a new exam or fix a bug. The server was made with **Node.js**, it simply serves the site, hosted with **Heroku**.

## How to build it:

To build the project:

* Install `Node.js`
* Clone the repository
* On the root folder of the repo, execute `npm i` to download the node modules
* The `main.local.js` file is the local server, without all Heroku trash. Without the decrypted firebase config file, push notification will not work. Run `node main.local` to run the local server.
* With a browser, test the site on `http://localhost:8080`
