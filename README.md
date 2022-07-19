To implement, we compile all the java files using javac *. Java using the linux shell terminal

When compilation is done, we create a stub and skeleton of the RoomManagerImpl by using the rmic tool.
This can be done using the command $ rmic RoomManagerImpl.

Then start the registry, and it has access to all java classes. A server address is specified and in this case out server address is 5000.
This is done by running $ rmiregistry 5000.

Then the server is started in this case the HotelServer, then the client is also started in this case the HotelClient.

These are done in different terminals shell by running $ java *.

Screens (screenshots).

These show the real-time running of the application in screen shots of different simulations.

Screen 1.

This illustrates the creation of stubs and skeleton of the RoomManagerImpl ($rmic RoomManager), and also the starting of the rmi registry ($ rmiregistry 5000).

 
 
Screen 2.

This illustrates starting of the server. This remains active waiting for requests from the Client ($ java HotelServer)

 
 
Screen 3.

These illustrate creation of 2 HotelClients to show multiple clients can communicate with the server. Further it shows the shell commands available for the client to choose from.

 

Screen 4.

From the pre-defined commands available to the use, this screen illustrates the list, guests and revenue commands.
The lists commands display available rooms with their pricing
The guests command displays registered guests.
The revenue command displays the revenue breakdown.

 

Screen 5

This simulation shows booking of rooms by multiple guests names, Josephine, Raymond, Maria, Frida and Barbra.
Then, after command to display registered users and aggregated revenue
 
 
Screen 6.

This simulation illustrates a scenario where some or all rooms have been booked and also the total amount accumulated from all booked rooms.

 


