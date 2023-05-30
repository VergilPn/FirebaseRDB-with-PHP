# Implement Member System (CRUD) with Firebase’s Realtime Database in PHP
This is a simple member login, logout and membership creation demo created using Firebase's Realtime Database and PHP. The application uses PHP to create the basic page structure and services and utilises html default UI components and styles without the addition of any CSS.

This program is based on the tutorial in this Youtube video by Devisty.<br>
(Youtube link: https://www.youtube.com/watch?v=MrcYfJiG-I8&ab_channel=Devisty)

In this demo you can see a basic PHP membership system. You can create a Realtime Database membership system by linking your Firebase's Realtime Database to the config.php file of the demo.

However, this is only a demonstration of how to use Firebase's Realtime Database in PHP, for security reasons it is not recommended to use Realtime Database as a membership system for your application. If you want to set up a real membership system it is recommended that you use Firebase's built-in Authentication.

# How to Use
To use this program, you can use XAMPP or any other method that opens PHP. You can then follow the steps below to start your local development server.

1. Download the source code for this program from Github.
2. Navigate to the program directory in the htdocs of the XAMPP file you installed.
3. Create your Firebase project and create a Realtime Database in the project. 4.
4. Place the link URL for your Realtime Database in the source code folder in config.php.
5. Change your Realtime Database rules to.
              {
                "rules": {
                  "user": {
                    ".indexOn": "email".
                    ".read": true.
                    ".write": true
                  }
                }
              }
6. Run the XAMPP control panel and start Apache.
7. Run your browser and type 127.0.0.1/FirebaseRDB-MemberSystem/index.php to view the demo application.


# Contributions
If you're interested in contributing tothis program, you can follow these steps:

Fork this repository.
Make changes and test in your local development environment.
Submit a PR (pull request) to submit your changes.
Thank you for your interest and contributions!
