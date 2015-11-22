# Quick-Share
Simple network sharing program

## Instructions
## Client
To upload or download a file you must perform the following actions:

1. Switch to client mode using `c`
2. Select the file you want to upload or save a downloaded file to using `file`
3. Set the server address using `conaddr {url}`
4. Open a connection to the server using `con`
5. Use either `upload` or `download`

## Server
To set up the server and then upload or download a file you must perform the following actions:

1. Switch to server mode using `s`
2. Select the file you want to upload or save a downloaded file to using `file`
3. Start the server and wait for a connection using `serveropen`. This will block untill a connection is made
4. Use either `serverupload` or `serverdownload`

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
* Added new client connection command to server
