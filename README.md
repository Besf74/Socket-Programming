# World Series Socket Program

## Objective
The following project is a Socket Program developed for a CYSE-250 course to practice Python socket programming in a client-server context. The program allows users to retrieve information regarding each World Series champion, loser, and MVP by inputting year. This interactive experience enforced basic programming concepts while simulating a basic networked communication system.

### Skills Learned
- Implemented and designed a client-server application with Python sockets.
- Enhanced understanding of lists, dictionaries, loops, and file I/O operations.
- Practiced modular programming with functions and organized logic sequence.
- Gained hands-on experience in sending and receiving data over a network.
- Improved debugging skills through trial and error in server-client communication.

### Tools Used
- Python (coded in Thonny IDE) for client and server sides.
- Socket Programming to create TCP communication between two computers.
- Text Files to save and load World Series data in an optimal way.
- Command Line Interface for testing and executing network-based scripts.

## Steps
### Server Code
The server loads the World Series data into a dictionary from a text file and listens for client connections. When a client sends a year, it responds with the champion, loser, and MVP of that year.

![Screenshot (15)](https://github.com/user-attachments/assets/22d2cada-39f9-467e-a309-44c08e80ec66)


### Client Code
The client connects to the server and sends an input of a year provided by the user. It then prints and gets the response.

![Screenshot (13)](https://github.com/user-attachments/assets/20ac0335-dcd9-4c51-a010-e960bf33c043)


### World Series Data File
Data was stored in a .txt file with each line in the following format:

year, champion, loser, MVP

The server loads this into a dictionary for fast lookups.

![Screenshot (16)](https://github.com/user-attachments/assets/d26991c9-2476-4b82-8913-0fcb6d2d47d0)


### Grading and Completion
Received a perfect score (100/100) from the instructor, with full functionality and good documentation.


![Screenshot (17)](https://github.com/user-attachments/assets/2c6250c4-7bfb-460d-81b0-55895784651a)
