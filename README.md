# DigiLance
A live chat application built using Firebase and React. This chat application can form the foundation for more complex applications that intend to incorporate a real-time chatting feature in them.

## What is Firebase?
Firebase (Google Firebase) is an application development software backed by Google. It can used in develop web and mobile(Android and iOS) applications. They are described as a Backend-as-a-service aka BaaS. 

> BaaS also stands for <i>Blockchain-as-a-Service</i> in certain contexts.<br> These <i>-as-a-Service</i> acronyms seem getting out of hand. We need an International Code of <i>-as-a-Services</i>

We will be using the Realtime Database and Authentication capabilities that Firebase provides, in this application. They also have other services on offer like Test Labs and Hosting services. 

### Realtime Database

The Firebase realtime database is a NoSQL database similar to MongoDB that stores data in a key-value format and is optimised for synchronizing data between the user machines and the central storage in the cloud. In our application, each text sent by the users is stored as a <i>"document"</i> which is essentially a key-value pair with the key being the userid and timestamp and the value being the text itself.

### Authentication

Firebase provides for different modes of authentication. Given the simplicity of the application in mind, our application uses the Google sign-in option to register and create users in the database
