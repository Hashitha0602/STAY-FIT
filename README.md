# STAY-FIT

Introduction:
StayFit is a web application for analyzing and logging strength training and body building data. StayFit has two different portals i.e exercise portal and recommendations portal. Apart from this, it also includes an admin portal. Exercise portal aims to present workout data in a way that highlights and encourages progressive overload and long term commitment. There are many workout tracking apps already available, what sets this one apart is the focus on data. If you want a workout application that guides you through a routine this isn't the tool for you. Exercise portal hasno server and works completely offline using IndexedDB. On the other hand, if you manage the routine yourself and track your workouts in a spreadsheet with a bunch of formulas and charts, you're probably the kind of person who would like this application. Recommendations portal provides 3 different subscription plans (Basic, Standard, Premium) where the user can choose their plan according to their requirement. These plans provide basic workout tutorials, workout recommendations and food recommendations according to the user’s weight. These plans recommend a particular type of workout according to his/her weight and the same follows with food recommendations i.e., for Breakfast, Lunch and Dinner based on the calorie intake.

Features:

Simple workout data entry supporting reps, sets, weight, duration, warmup and failure sets
Musculature visualizations
Intensity and volume calculations
Import from CSV
Export to JSON
Track and visualize personal records
Exercise search
Punchcard graph
Supports multiple workouts per day
Proper time zone support (important for people who travel)
Workouts portal works offline, no network connection required
Lots of charts
Provides different subscription plans for users (Basic, Standard, Premium), paid through payment gateway (PayPal).
Basic plan provides workout tutorials
Standard plan provides workout recommendations including features of basic plan.
Premium plan includes food recommendations including features of standard
A chatbot for conducting an online chat conversation via text.
Admin portal for providing recommendations on daily basis.
Lightbox extension for larger view of pictures and gifs.

3 modules:

Exercise portal
Recommendation's portal
Admin portal
Software Requirements:
-> Frontend :- HTML,CSS,JS,JQuery
-> Backend :- PHP
-> Styling :- Bootstrap
-> Database :- MySql

Hardware Requirements: -> Operating System :- Windows/Mac/Linux
-> Browser which supports javascript and Indexed DB (Browser Database)

Step-wise instructions:

Download the zip file of this repository
Unzip the folder
Place the folder into htdocs of xampp folder (C:\xampp\htdocs)
Open database/admin.sql file
Import it to the wamp/xampp folder (Note: Username for phpmyadmin is ‘root’; password is ‘’)
Opening file for the project is index.php
Exercise portal and recommendations portal can be accessed from the same page.
To login as admin, use initial credentials (Note: Username is admin, password is admin)
Logout will directly redirect the user as well as admin to home page
dbconfig.php contains the data for the connection of the localhost to the database of phpmyadmin. Login credentials for phpmyadmin can be restructured there as well.

For furthur assistance: @hashithaa0602@gmail.com
