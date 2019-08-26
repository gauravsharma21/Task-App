# Task-App
This is a REST API which acts as a backend to connect to a database hoisted on MongoDB Atlas for a signing up a user. Only a signed user
can create, modify or delete his tasks on the cloud database. The link to the API is :

http://common-task-manager.herokuapp.com

# Features
* **Mongoose** is used to create object model of tasks and users
* Entered password is hashed 8 times before storing in the database using **BcryptJS**
* Every client gets a 64bit authorization token to access and modify his tasks in the database using **JSON Web Tokens**
* Buffer of the avatar is stored in the database using **Multer**
* **SendGrid** mail API is used to send Welcome email to newly joined users. Cancelation email is sent to user who deactivates his account

**P.S.** The front end of this project is and Android app currently under progress using **React-Native**. Link to the repository is here:

https://github.com/gauravsharma21/Task-manager-android
