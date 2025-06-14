# Example how to use Auth0 with React+Spring


What you need to run the project:

1. Dowland project from this repository
2. Create Single Page App in your Auth0 account. Here you can see "Create a new application" button and some instructions if you want to read it: https://auth0.com/docs/quickstart/spa/react/interactive
3. Create API in your Auth0 account. Here you can see "Create a new API" button and some instructions if you want to read it: https://auth0.com/docs/quickstart/backend/java-spring-security5/interactive
4. Then open 'frontend' project in Visual Studio Code for example and do "npm instal".
5. Open 'api' project and instal all maven packages. For example in IntelliJ IDEA it is 'Sync All Maven Project' button.
6. Then you have two ways:
   - If you WANT the example to work with the database:
     Replace all required variables with your own in application.properties (api file) and properties.js (frontend file).
 
   - If you DO NOT WANT the example to work with the database:
      Comment out the variables specified in the application.properties file (api file). Comment out the call to the Users component in the App.jsx file (frontend file). Replace all the necessary variables with your own in application.properties (api file) and properties.js (frontend file)
     
7. Change requests if your projects run on other ports
8. Run both projects and enjoy the result
