# Bucketlist

Stop dreaming about your bucketlist and start living it.<br>
Because energy flows where intention goes.<br>
Set your bucketlist intentions today!

## Deployed Site
[Live website](https://bucketlist-2020.herokuapp.com/.)
![](static/img/website.JPG)

## UX 

### User Stories
* As a new user I can look at other peoples bucketlist intentions.
* As a registered and logged in user I can set my own bucketlist intententions.

### Strategy
This website is for people who want to set there intantions instead of keeping them just in their head.

### Scope
* A Landing Page that is easy to navigate.
* A navigation bar and footer that change depending on whether the user is logged in or not.
* A register and login form for users to either create a new account or to log in.
* A Profile Page for users to view/edit/delete their posts, and an option to delete their account. xxxxxxxxxxxxxx
* A Sign Out button that is easy to find on every page in the navigation bar and footer.
* An Intentions page where users can see all the bucketlist intentions on the website.
* An admin page to manage the divisions.

### Structure
* Color Scheme: green
* Every page has the same header and footer. Only the menu items change, depending on if the user is logged out, logged in or it's the admin
* intentions.html shows all added intentions from all users
* register.html shows a materialize card with two required fields: username and password
* login.html is the same as the register.html
* etc etc

### Skeleton
* Header:
* Menu
* Footer:
* Homepage/All Intentions
* Register page:
* Log In page:
* Profile page:
* Add Intention page:
* Manage Divisions page: only accessable by the admin account.

### Surface
* Font Family:
* Text Color:
* Colors:
* Header:
* Footer
* Homepage/All Intentions
* Register page:
* Log In page:
* Profile page:
* Add Intention page:
* Manage Divisions page

### Mockups
The following wireframes were created using Balsamiq to design the website layout options.<br>
![](static/img/homepage.JPG)
![](static/img/register.JPG)
![](static/img/login.JPG)
![](static/img/profile.JPG)xxxxxx
![](static/img/add_intention.JPG)
![](static/img/manage_divisions.JPG)

### Database Schema

## Features
The webpage consists of the following features:

__The navigation bar__<br>
![](static/img/navbar_loggedout.JPG)
![](static/img/navbar_loggedin.JPG)
![](static/img/navbar_admin.JPG)

__Footer__<br>
![](static/img/footer.JPG)

__Registration page__<br>
The form is set to give feedback if username is too short. There is also error checking against confirmation password mismatch and some basic password criteria. Passwords are hashed using bcrypt and then saved to the database, hashed passwords are compared on login attempt. Once registered the user ill be redirected to their profile page. There is also a link to go to the sign in page here.
![](static/img/register_screenshot.JPG)

__Login page__<br>
The login page is simple, users can enter their username and password. This is authenticated in python and feedback is given if the credentials are incorrect. For security all passwords are hashed and the hashed versions are compared. Successfully signing in to the site will direct the user to their profile page. There is also a link here to register a new user.
![](static/img/login_screenshot.JPG)

__Profile page__<br>
The profile page is a users space to 
This is also where you will delete your profile.

__Intentions Page__<br>
Read (view) all intentions
This page shows all the posts made on the website.

__Add Intention__<br>
Add a New Intention.
A simple form in the same style as all other forms on the website. When a user is logged in they can use this form to add a new intention. The following details need to be filled in on this form:
When the Submit button is pressed the post is sent to the Mongo database and will show up on the main intentions page.
![](static/img/add_intention_screenshot.JPG)

__Manage Divisions__<br>
Add a New Division.

### Code structure

### Features Left to Implement

## Technologies

### Languages
* [HTML5](https://en.wikipedia.org/wiki/HTML5) - Used as the main language for the templates 
* [CSS](https://en.wikipedia.org/wiki/Cascading_Style_Sheets) - Used for styling the webpage
* [JavaScript](https://en.wikipedia.org/wiki/JavaScript) - Used for some front end functionality
* Python3 - Used for backend data manipulation 
* PyMongo - Used to communicate with the mongoDB database 

### Libraries/Frameworks/Tools
* [Github](https://github.com/) - Used for version control 
* Flask 1.0.2 - Used as the main framework for my application 
* [Pixabay](https://pixabay.com/) - Free online images. Used for some images on website 
* [Fontawesome](https://fontawesome.com/) - Used for some icons on the website 
* [Materialize](https://materializecss.com/) - Used as the main frontend framework 
* [Heroku](https://heroku.com/) - Used to host the website 
* [GitHub](https://github.com/) Used to store my project source code 

### Databases
* [MongoDB](https://www.mongodb.com/)- Used as the main database technology

### Testing
* [W3C Markup](https://validator.w3.org/) - Used this to check my HTML for errors and typos
* [W3C CSS](https://jigsaw.w3.org/css-validator/) - Used this to check the validity of my CSS
* Google Chrome Developer Tools for testing different divice sizes
* [Responsinator](https://www.responsinator.com/) - for testing different divice sizes

## Deployment

### Deployment left to be implemented

### GitHub repository....

## Credits

### Content
The content is made up and written by me. The intentions are added by diffirent users.

### Media
The photos used in this website were obtained from [Pixabay](https://pixabay.com/).

### Acknowledgements
* [Code Institute course](https://codeinstitute.net/) course & Student Care
* [YouTube](https://www.youtube.com/)
* [Slack](https://slack.com/) community
