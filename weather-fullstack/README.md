# Weather API Fullstack Webpage 
This is a full-stack application. The back-end is created with Java and is used for the purposes of security. The front-end is created with Vue JS, a JavaScript framework, for the purpose of consuming the openweathermap.org api. The back-end is responsible for storing the api key in a secure location and to authenticate users before they can access the entirety of the website. The user's information is stored inside a database, weather_fullstack, created with a shellscript and managed with Postgresql. Starter code is from the Tech Elevator Capstone project.
## NOTE
The application uses a constant called **API_KEY** inside weather-fullstack/weather-fullstack/java/src/main/resources/application.properties. Currently it is set to *"Your API Key here!"*. To have the application execute successfully, you must visit https://home.openweathermap.org/users/sign_up to get a free api key and replace the constant with your own.
## Instructions
* register a new username and password
* sign in (if successful, you will see a message stating "You must be authenticated to see this")
* navigate to the Weather tab
* enter zipcode
    * displays the temperature, the adjusted temperature, and an icon of the current weather
## Project Setup - Java
* replace *Your API Key here!* with your personal api key
* run create.sh within the database folder
* run the application
## Project Setup - Vue
```
npm install
```
### Compiles and hot-reloads for development
```
npm run serve
```
### Compiles and minifies for production
```
npm run build
```
### Lints and fixes files
```
npm run lint
```
### Customize configuration
See [Configuration Reference](https://cli.vuejs.org/config/).
