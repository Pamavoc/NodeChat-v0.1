# NodeChat-v0.1

made with node.js, socket.io, express.js and scss

https://com-pamavoc-nodechat.herokuapp.com/


<b>HOW IT WORKS</b> 

- The app is split in 2 parts : server.js /client.js
- We have a node server running with the framework express.js in the background of our site. 
- The server.js file is used to retrieve some files (client file, css..) & to communicate with the client.js & set routes.
- He's here to listen and to communicate with the client.js
- When something is done on the client side, we have an event associated with it in our server.js file
- For example, when someone is connecting to our client.js we have an of event listener with io().
  > io.on('connection', function(socket) {
    console.log('connexion detected')
    }
    
   
<b>ROADMAP</b> 


v0.1 : basic chat in realtime with client/server. 

v0.2 : username support.

v0.3 : colors for the chat.

v0.4 : sound for the chat

v0.5 : real UI.

v0.6 : history of the chat with a DB.
