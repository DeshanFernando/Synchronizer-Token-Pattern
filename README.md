***Synchronizer Token Pattern***

This project demonstrates how to use CSRF Tokens and Session IDs to validate sessions and users using PHP.

Setup Requirements: WAMP (for windows users) or LAMP (for Linux users) installed on your machines.

Running the App: Clone this repository. Use master branch!

Steps:

Copy all the files in the directory. Paste the files in to a directory in the path /var/www/html (for LAMP users) Open a web browser and navigate to http://localhost/[directoryname]/

User :

username -> admin and password -> pass to log in.

Description :

Upon successful user login, the server generates a Session ID and a CSRF Token for the session. Session ID is set as a browser cookie. When user submits the form, The server validates whether CSRF Token matches.


Blog: https://securedprogramming.blogspot.com/2019/05/synchronizer-token-pattern.html
