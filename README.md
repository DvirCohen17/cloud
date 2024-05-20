# cloud
This is a multy server-client project.
you can use it to create and write a text file with your friends in live, give permission to other to join your files, each file also contain a private chat.
in this project i did only the sync server and the client.
 
To see the code you can go into the "code" branch.

To use this project alone there is a few steps
**notice that there are some bugs when running it with the dockers**
i have an additional project with just the sync server that works better and also have some more featuers at: https://github.com/DvirCohen17/cloud_Cyber/tree/main

1. go into the "run-project" branch and download all the files.
2.    
(optional - to use with dockers otherwise the files saves localy in the server's computer)
3. you need to download docker desktop in order to run the docker for the server.
4. run the docker using the cmd in the same directory off the files from the "code" branch then ude 'docker build -t *name* .' and then 'docker compose up'.
5. run the cloud server.exe.

6. take the main_server.exe and put it in a folder, then go to the client and download it in a separate folder, add the necesry changes to the config for the server ip and then run the "main_server.exe" and then "client.exe".
