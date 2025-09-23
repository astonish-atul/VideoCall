# VideoCall!

## Connect with love.

### Introduction:

VideoCall! is a node.js based video calling application which uses socket.io and peerjs lib to establish peer to peer connection and come
with numerous features including

1. Group video call built over google authentication
2. Screen sharing feature along with real time chat
3. audio and video control feature
4. Google authentication , shareable whiteboard
5. participant tracking , shareable invite link and many more ...

### How to use:

1. Clone the repo from the link
2. Install all dependencies listed in package.json using "npm install"
   \*if vulerabilities detected run "npm audit fix --force"
3. create a .env file in the same dir as of server.js with the str shared below
4. Run npm start (and logon to localhost:5000)
### Basic Note:
.env file will include\
CLIENT_ID=*************\
CLIENT_SECRET=********************\
CALLBACKURL=http://localhost:5000/google/callback

Get client id and client secret by following these steps:
1. create "project" on google developer console
2. set the URI to localhost:5000 and callback URI to localhost:5000/google/callback

