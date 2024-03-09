# ChatSystem
Chat server and client using C socket programming

The system should allow at least two users to chat with each other through their terminals (Command Line Interface). Before starting a chat session, every user needs to log in to the system using the registered username and password. 

The system keeps and shows a history of the conversation.

## Running and Using the Code
(open terminal)
cd <file location>
gcc server.c -o server
./server

(new terminal)
cd <file location>
gcc client.c -o client
./client
Enter User Name: beyza
Enter Password: 987

(new terminal)
cd <file location>
gcc client.c -o client
./client
Enter User Name: derya
Enter Password: 123

Last message should be "end"

If you run the code again the first thing you will see in the terminal will be the previous (saved) messages.
