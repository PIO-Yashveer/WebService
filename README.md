Creating a Web Server on IBMi
.
First we need to create a http server.

We can use IBMi Navigator to create a new http server.

Create a new http server.

Provide configuration for the server.

Once the server is created, edit the configuration file.

The Server.conf file in this folder is used for http server configuration.

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

Give plain text in the body of the URL, which you want to convert.

Program will return converted EBCDIC character data to brower.
