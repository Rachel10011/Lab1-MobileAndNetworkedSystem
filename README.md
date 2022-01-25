# Lab1-MobileAndNetworkedSystem
In this lab you will enhance the capabilities of two applications: a client application, and a server application. The objective is to review how these two applications interact with one another using TCP concept, while refreshing your coding stills in C/C++ using Sockets.


CSCN72050 – Lab1
Review of Sockets – TCP/IP
Overview
In this lab you will enhance the capabilities of two applications: a client application, and a server application. The objective is to review how these two applications interact with one another using TCP concept, while refreshing your coding stills in C/C++ using Sockets.
Clone the Visual Studio Solution repository CSCN72050_Lab1 folder and perform the following modifications of the code:
See eConestoga for the Clone Link
PART 1: Updating the Cloned Code
STEP #1
Update the code so that your client can keep sending messages until it sends the word “quit” in a message. The server should display each received message. After the “quit” message, both the client and server applications should exit.
STEP #2
Update your code so that your server will send the string “Received Message” to the client, confirming that it has received the user defined message. The client should output this received message on its own screen and then be ready to send more messages until it sends a “quit” message. After sending “quit”, both the client and server applications should exit.
STEP #3
Update your code so that your server will not close after receiving a “quit” message, instead it will just start accepting new connections. Test your solution by starting and exiting client applications several times.
STEP #4
Make a copy of your “client.cpp” and “server.cpp” files and rename them as follows:
• Client.cpp  Client_Part1.cpp
• Server.cpp  Server_Part1.cpp
STEP#5
Run your Client and Server applications side by side using two command prompts (don’t use visual studio). Type in at least 3 messages in your client application followed by the “quit” command. Take a screenshot of your client and server applications (as shown in the Appendix below) and paste it in the box below.
PART 2: File Streaming
For this next part you are going to update the client/server code to stream a text file one character at a time over the TCP/IP interface.
STEP #1:
Change your client application so that it will ask for the file name of a simple text file. Then, it should send the contents of the file, character by character, to the server. At the server, your code should change so that it creates a file called Rx.txt which should be filled with the contents coming from your client. The Server should continue to send “Received Message” after every packet it receives.
STEP #2:
Run your Client/Server with the Hamlet.txt file located in the resources of the Visual Studio Solution space you cloned.
STEP #3:
Make a copy of your “client.cpp” and “server.cpp” files and rename them as follows:
• Client.cpp  Client_Part2.cpp
• Server.cpp  Server_Part2.cpp
Rubric
See eConestoga for details.
What to Hand In
Once you have completed your lab upload the following files INDIVIDUALLY to eConestoga:
• A copy of this PDF form (without modification)
• Client_Part1.cpp
• Server_Part1.cpp
• Client_Part2.cpp
• Server_Part2.cpp
• Rx.txt
Do not compress these files in anyway. Uploading a Zip, Tar, 7z, etc… file will result in a 10% penalty for not following instructions.
APPENDIX
Your final screenshot should look something like this.
