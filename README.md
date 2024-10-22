# CNT4007 Project 2

### Steps to compile and run content
1) Unzip file contents if not done already
2) Open a bash terminal in the current directory ("../NetworkingP2")
3) Run make command to compile scripts
```bash
make
```
4) Split your current terminal or open up another one in the same directory
5) In one terminal run the following command to start the server
```bash
./server
```
6) In the other terminal, run the following command to start the client
```bash
./client
```
7) The client should now be connected to the server and you can run the commands listed
8) Additionally you can start more terminal and run the client command to connect to the server (up to 100 concurrent times)

Our script will only read txt files, so if you wish to do addtional testing by adding or deleting songs from the server (in ./Server_Files/songs) or songs from the client (current directory .), you will have to do so by using txt files.
