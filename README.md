# sekai
Open 3d world written in nodejs

#Target: 
        
  Open and free 3d spaces for all people.
  We start this, you can make from this all what you want.
  This project - idea and little prototype code.
  You can make from it small room or huge world.
  Fork and edit, copy and distribute. Be happy.
  All in your hands, people of humanity.


#Simple description:

Two parts:

1. Server:

   Store all objects and fast sync it between with clients.      

2. Client: 
   
   Interpret object data from connected 
   servers (client can connect to many server) and 
   render it in 3d space.
   Give user interface for manipulate objects in servers.

Server part: Firebase or other fast sync database.

Client part: Use project A-Frame (https://aframe.io/) for this with add
             components for more functionality.

Idea: assets (3d model, texture, sounds) simple save in web servers and
      object include its URL's in parameters, client load assets from URL's
      and render or play it.


I find:

Project A-Frame
(https://aframe.io/)
Little module for multiplayer with aframe and firebase
(https://github.com/ngokevin/aframe-firebase-component)

I think this good base for project.

Dont forget configure parameters for your Firebase database.

#TODO: from dreams to code. and learn english :)

