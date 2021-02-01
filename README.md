# DeployeAngularInFireBase
Deploy proyect in Firebase,



### Add componente de angular

ng add @angular/pwa


### Global firebase-tools

 npm i -g  firebase
 npm i -g  firebase-tools
 
 
### Login Firebase

firebase login
? Allow Firebase to collect CLI usage and error reporting information? Yes


### Inicializamos Firebase

firebase init
? Are you ready to proceed? Yes
? Which Firebase CLI features do you want to set up for this folder? Press Space to select features, then Enter to confirm your choices. Hosting: Configure and deploy F
irebase Hosting sites


? Please select an option: Create a new project
? Please specify a unique project id (warning: cannot be modified afterward) [6-30 characters]:
 transgas
? What would you like to call your project? (defaults to your project ID) transgas

? What do you want to use as your public directory? dist/front
? Configure as a single-page app (rewrite all urls to /index.html)? Yes
? Set up automatic builds and deploys with GitHub? No
+  Wrote dist/front/index.html


### Build the proyect

ng build --prod

### Push Firebase

firebase deploy

+  Deploy complete!

Project Console: https://console.firebase.google.com/project/transgas/overview
Hosting URL: https://transgas.web.app





https://www.youtube.com/watch?v=jI0eR95U0Z0&ab_channel=DominiCode
