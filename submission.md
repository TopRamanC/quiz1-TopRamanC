# Quiz #1 : Assessment and Planning 

### Date: November 10, 2021
### In Class/Lab Quiz:
### Due:
* Morning Class:  11:45
* Afternoon Class: 5:45


---
## Name: Ramanpreet Chadha                                  <!-- answer -->


1. A URL is comprised of a number of components.  Consider the following URL:

  ``one://two:three@four.five.size:seven/eight/nine/ten?eleven=twelve&thirteen=fourteen#fifteen``

  * Provide both the name and value of each component.
    1. scheme: "one"                                    <!-- answer -->
    1. host: "two"                                                 <!-- answer -->
    1. port: "three"                                                 <!-- answer -->
    1. domain: "@four.five.size"                                                 <!-- answer -->
    1. path: "seven/eight/nine/ten?"                                                 <!-- answer -->
    1. Query_string: "eleven=twelve&thirteen=fourteen"                                                 <!-- answer -->
    1. Fragment: "#fifteen"                                                 <!-- answer -->
    
    <!-- Add more lines as needed -->

1. In the following code block, provide the git instructions necessary to add a new file to the remote repository: git@github.com:org/project.git (You should presume that you don't have a copy of this repository on your local computer.)
   ```
     Step 1: Git clone git@github.com:org/project.git to your local machine.
     Step 2: CD into the repository on your machine through the CLI.
     Step 3: Add your new file in the cloned repository on your local machine.
     Step 4: Use the following command to add file to github: git add <filename>
     Step 5: Use the follwoing command to commit your changes: git commit -m <message>
     Step 6: Use the following command to push your changes to github: git push
     Step 7: Use the command "git status" to make sure everything is updated onto the github respository.                                                   <!-- answer -->
   ```
   <!-- You many add any number of lines in the above code block that you need. -->

1. Provide the Apache Directive used to perform the requested action
   1. Position the location of root location of the website at:  /var/www/html
     * DocumentRoot /var/www/html                                                 <!-- answer -->
   1. To disable the user "steve" from having a web presence on your server.
     * Userdir disabled steve                                                  <!-- answer -->
   1. To create an alias between the URI: /marketing and the file: /user/marketing/www
     * Alias /marketing /user/marketing/www                                                 <!-- answer -->
   1. To define the location of the error log to be: /var/log/apps/apache/error.log
     * ErrorLog /var/log/apps/apache/error.log                                                 <!-- answer -->


1. What is the command used to create the user "steve" within your apache container?
    *  RUN useradd steve                                                <!-- answer -->


1. What does the "AllowOverride" Directive do?
    * Allows you to override apache configurations. We needed to enable this for our current lab so we could use a .htaccess file.                                                 <!-- answer -->


1. Given the following command, provide the corresponding HTTP Request Header:
    * curl  https://www.csun.edu/~steve/roster/input/value/input/value
    ```
      GET ~steve/roster HTTP/1.1
      Host: www.csun.edu
      Accept-Language: en-us
      Content-Type: text/html
      Content-Length: (some values in bytes)
                                                       <!-- answer -->
    ```                                                      
    <!-- You many add any number of lines in the above code block that you need. -->

1. The CGI standard defines a number of environment variables that are provided to a CGI program.  Identify and explain the purpose of 6 of these environment variables.
   1. QUERY_STRING:  the part of URL after ? character.             <!-- answer -->
   1. REQUEST_METHOD: GET, POST                                                              <!-- answer -->
   1. REQUEST_URI: the URI of the requested document.                                                              <!-- answer -->
   1. CONTENT_TYPE: the conetent type declared in the HTTP response                                                              <!-- answer -->
   1. CONTENT_LENGTH: the length of the HTTP request body in bytes.                                                              <!-- answer -->
   1. GATEWAY_INTERFACE: the CGI interface that the server is using such as CGI/1.1                                                               <!-- answer -->
   1. SERVER_PROTOCOL: the number of the server protocol such as HTTP/1.1                                                               <!-- answer -->


 1. Consider the following URL and regular expression used to process this string:
    * URL:   ``http://www.fake.org/marketing/john.smith/code=10325/app/input``
    * regexp: ``"^marketing/([a-z]*.[a-z]*)/(code=[0-9]{4,6})/(.*)$"``

    Define the value of each of the following back references
    1. $1: marketing                                                          <!-- answer -->
    1. $2: john.smith                                                          <!-- answer -->
    1. $3: code=10325                                                          <!-- answer -->
    1. $4: /app/input                                                          <!-- answer -->

1. There are a number of different types of files.  Each of these file types can be identified by a single character in the output of the command ``ls -l``.  What are these types of files:
   1. -: a regular file
   1. p: named pipe                                                         <!-- answer -->
   1. l: symbolic link                                                         <!-- answer -->
   1. d: directory                                                         <!-- answer -->
   1. b: block device                                                         <!-- answer -->
   1. c: character device                                                         <!-- answer -->
   1. s: socket                                                         <!-- answer -->

1. Describe each of the following:
  - process: a list of steps or actions.                                                     <!-- answer -->
  - environment: the hardware of your machine and the operating system being used on that machine.                                                 <!-- answer -->
  - stdin: standard input.                                                       <!-- answer -->
  - $?:  the exit status of the previous command that was executed.                                                         <!-- answer -->
 
