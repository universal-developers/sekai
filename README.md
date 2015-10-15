# sekai
Open 3d world written in nodejs

Simple description:

Two parts:

1. Server:
   
   Store objects and its behavior in database, 
   work with objects behaviors and give object parameters
   to connected users. 
   Load client part to user browser if user conected.

2. Client: 
   
   Interpret object data from all connected 
   servers (client can connect to many server) and 
   render it in 3d space.
   Give user interface for manipulate objects in servers.


Server part: Nodejs with persistent store objects in database.

Client part: Javascript code for browsers with 3d engine Three.js
             for render. Client part load to users browsers if it 
             conect to server. 


Idea: assets (3d model, texture, sounds) simple save in web servers and
      object include its URL's in parameters, client load assets from URL's
      and render or play it.

#TODO: from dreams to code. and learn english :)
 


