## Project details

#### Project name

###### **CS 32 Final Project**: Pomodoro Party

#### Project description

###### We build a pomodoro timer app that you can share with friends and track your TODO list. The app has a login system, a dashboard, and lets the user select how long they'd like to work for. 

#### Team members and contributions

###### Sabrina Chwalek (schwalek), Afia Akosah-Bempah (aakosahb), Angela Yeung (ayeung9), Maxime Seknadje (mseknadj) 
###### 

## Design choices

###### Our App class is the main high-level class of the program. From there, we have several classes which represent different pages in our program, for example, the login page, the register page, the dashboard page, and the party page. The party page is where the majority of our functionality is, and it contains our pomdoro timer and todo list, which each have their own classes. 

###### We used a realtime database and an authetication database in firebase though to handle our backend and store/update user data. 

#### Noteworthy Design Decisions

###### We set up a realtime database in firebase that keeps track of the current user sessions and allows other users to join someone's session. We also use a firebase database to store our user's login and account information. 

## Errors/Bugs

###### Our register page is a bit glitchy where it doesn't redirect you to the dashboard. Once you start the timer and join a new session, our pause button is also glitchy. 

#### Explanations for checkstyle errors

###### In your terminal navigate to the src directory and run the following command: npm test

#### Build and run your program

###### In your terminal navigate to the src directory and run the following command: npm start
