Creating a Web Server on IBMi
.
First we need to create a http server.

We can use IBMi Navigator to create a new http server.

Create a new http server.

Provide configuration for the server.

Once the server is created, edit the configuration file.

The Server.conf https://github.com/PIO-Yashveer/WebService/blob/main/Server.conf file in this folder is used for http server configuration.

Now Start the Server (Restart if already running).

Now the Server is Created. 

Create a program to handle GET request.

Fetch data from database using Get request.

Create a https://github.com/PIO-Yashveer/WebService/blob/main/GETREQ.txt RPG program which can hanlde get request.

This Program will send the data from a physical file to browser.

Send Get request through URL.

Data will be displayed on browser.

Create a program to handle POST request.

Convert TCP data to EBCDIC character set.

Create a https://github.com/PIO-Yashveer/WebService/blob/main/POSTREQ.txt RPG Program which can handle post request.

This Program will convert TCP data to EBCDIC character set.

Send Post request through URL.

Create a program to handle consuming api using GET request.

create a https://github.com/PIO-Yashveer/WebService/blob/main/GETC.txt RPG program which can handle get request

This program will POST data to external api

Create a program to handle consuming api using POST request.

create a https://github.com/PIO-Yashveer/WebService/blob/main/POSTC.txt RPG program which can handle post request

This program will POST data to external api

Create a program to handle consuming api using PUTC request.

create a https://github.com/PIO-Yashveer/WebService/blob/main/PUTC.txt RPG program which can handle PUT request

This program will update data into external api

Create a program to handle consuming api using DELETE request.

create a https://github.com/PIO-Yashveer/WebService/blob/main/DLTC.TXT RPG program which can handle DELETE request

This program will Delete data into external api
