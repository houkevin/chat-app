# chat-app
Contains NodeJS, HTML, CSS.  It functions like a normal chat application.  First the user will need to input a display name and the room that they want to join.  Then after the user enters the room, there will be a chat log sent by the chat bot in the room that the user has entered the room.  The user will be able to start chatting by pressing the text box and entering some text.  Since new messages in a chat app appear starting from the bottom, there needs to be an autoscrolling function that will keep the text moving up and out of the screen as more messages come in.  The scroll function checks the height of the container and the height of the message, then moves the scroll accordingly.  Additionally, there is a function that does not allow profanity by first checking the contents of the message before sending it out.  If the message contains any profanity, it will send a message to the user saying that profanity is not allowed and not allow for the message to be sent.  At the end when the user is done chatting, they can disconnect from the room.  When they disconnect from the room the chat bot in the room will send another chat log saying that the user has exited the room. 
