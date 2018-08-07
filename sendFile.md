# Project Title

Utilizing client server functionality we can send a file from one endpoint  to another. 

## How it works

1. The first thing the script does is caculate the buffer of the file, this number is sent from the client to the server.

2. End point allocates file size and begins transfer. 

3. End point saves file in an directory.

4. The user must edit this directory to where they would like to set the path to.

5. A working internet connection is required to perform the file transfer.

6. The user must know the extension of the particular file being sent, alternatively they can just name the file something abitrary and chnage the extention in the target system.


## Getting Started

1. Download code

2. Give the script executable rights

3. type sendFile.py -t (your IP) -p (your port) -f (your file dir)

   a. sendFile.py -l -p 5000                                                  -----> server is listenining.

   a. sendFile.py -t 192.168.1.1 -p 5000 -f C://hello/notepad.txt             -----> file is sent to server.

### Prerequisites

Python 2.4 and above


## Built With

Pycharm

## Authors

**Juan A Wagner** - *Initial work* - [SPAWAR](https://www.linkedin.com/in/juanwagner/)
