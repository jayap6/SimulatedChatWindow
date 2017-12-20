# SimulatedChatWindow

This is a simulated chat window application using JavaScript and HTML5. The filename of the HTML/Javascript file is “SimulatedChatWindow.html”

Design Details

Objects

1.	List of connections for the user who has logged in.
2.	Connection -> username/name/password
3.	Chat Window -> contains the list of connections (for the user who has logged in) on the left side and the place/text area for sending/receiving the messages on the right side.
4.	The window (place/text area for sending/receiving the messages)

Object Oriented Analysis/Design

Diagram to be added later...

Class Diagram

ListOfConnections 

-Connection[]

+getUsers()

+addUser(username, firstname, lastname, password)

+addConnection(connection)

+removeUser(username)

+removeConnection(connection)




Connection 

-username

-firstname

-lastname

-password


+getUsername()

+getFirstname()

+setFirstname(String firstname)

….all get and set methods…

ChatWindow (Interface)

+login(username, password)

+getConnections() 

+chat(message)

Note: Encryption for the password is required. Chat is a mechanism for sending and receiving messages. 


Flow Chart

1. The User logs in (login window) 
2. The user sees the list of users who have joined/logged into the chat on the left side. 
3. The user sends a message by clicking on the “Send” button on the window on the right side. 
4. The message gets displayed on the text area/scrolling pane.
5. Newest messages should always appear at the bottom. Older messages should appear above newest. The chat window should scroll when needed. 
6. The user responds by sending another message which gets displayed on the text area/scrolling pane. 

  Note:
  The data can be separated by having the JSON formatted data in a separate javascript file.

