# wowchat
(documentation)



# Introduction 

   This document provides comprehensive guidance on using and developing the Real-Time Chat App (wowchat).
   The application allows users to engage in real-time text conversations, where user can able to message directly to his friend and even make a group on the chatting app.

     
 •	Technologies Used
 1. Frontend: HTML, CSS, JavaScript (React)
 2. Backend: Node.js, Express.js
 3.	Real-time communication: getstream.io Api
 4.	Authentication: bcrypt and crypto (Node.js library)

• Features
1. Real-time text messaging
2. Multimedia sharing (images, videos, documents)
3. Group chats
4. Emojis and stickers
5. Search functionality

![image](https://github.com/ashwaniraj0813/wowchat/assets/122291624/2bfb364d-2306-4256-91d8-604e0dccec30)


   

# Getting started

• Installation

To install the Real-Time Chat App, follow these steps:
1.	Clone the repository:
2.		Navigate to the project directory:
3.		Install dependencies: npm install
4.		For server-side go to server file and run node index.js
5.		For client run go to client file run npm start


•	Running the App

1. Access the app in your browser at http://localhost:3000
2. It can also be access by this url:______ as it is launched on Heroku.




# User Guide 

• Registration and Login

1.	User can register for an account using phone no. and can generate own username and password for the reference image is attached below.
   
   ![image](https://github.com/ashwaniraj0813/Ashwani-Raj/assets/122291624/bc8604da-94d4-4033-abd5-23585b2116a2)

3. After the registration user can login using their username and password for the reference image is attached below.
   
   ![image](https://github.com/ashwaniraj0813/Ashwani-Raj/assets/122291624/f05b20a1-21a3-4795-a09c-03d5426fb8bf)


• Chat interface
1.	Select the contact in direct message to open the chat interface
2.	Messages are displayed in real time
3. You can create a group by clicking on + icon of channel 


•	Multimedia Sharing
1. User can share images, videos and documents with their contact.
2. Multimedia files are displayed inline within the chat interface.

# Libraries used

• Libraries used in making server-side application are as below:
1. Bcrypt
2. 	Crypto
3. 	Dotenv
4. 	Express
5. 	Getstream-chat

• Libraries used in making client-side application are as below:
1. Stream-chat
2. Stream-chat-react
3. Universal-cookie







