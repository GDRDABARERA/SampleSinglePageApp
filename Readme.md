1) Start IS locally

2) Register a Service provider in IS using Oauth2/openidConnect (Give the call beck url as http://localhost:5000/oauth_callback.html)

3)Unzip the shared folder. You can find the configuration details in app.js file. Open the oauth/js/app.js file.

4)Change the IS_PORT(If you are using port offset), change the CLIENT_ID(Which you can get from step(2)).

5)Save the changes.

6) Now you need to run the application. In order to run our SPA you need to install npm. If you are using ubuntu the link [1] would be helpful. I have installed npm using NVM. You can install npm according to your preference.

7) After successfully installed, you need to build the application and start the server. You can use the following commands.You must run these command from the root folder of SPA (In our case inside oauth folder)

             -> sudo  npm install -g reload
             -> npm install -g serve (To build the application)
             -> serve (to start the server)
             
8) Now the server will start with default port 5000(If you don't have any application running on port 5000. If your port 5000 already occupied then server will get started from the next port available. You may need to modify the app.js file if your angular port is started other than 5000 port).

9) Access the server  http://localhost:5000 . You will get the the following page.




