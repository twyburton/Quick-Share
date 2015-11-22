# Quick-Share
Simple network sharing program

## Instructions
## Client
To 

## Server


## Commands
### Switch Commands
* q - Quit
* c - Set Client Mode
* s - Set Server Mode
* file - Choose file to process

### Client Commands
* conaddr {url} - Set the connection server address to {url}
* printconaddr - Print the currently selected address
* con - Connect to server
* closecon - Close connection to server
* upload - Upload file to server (Blocks)
* download - Download file from server (Blocks)
* clientclose - Stop client mode

### Server Commands
* serveropen - Start the server (Blocks)
* servernew - Wait for new client connection (Blocks)
* serverupload - Upload file to client (Blocks)
* serverdownload - Download file from client (Blocks)
* serverclose - Stop server mode and shutdown server
		
## Changelog
### Version 0.3
* Added server > client transfer
