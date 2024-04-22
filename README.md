# TweetApp-FrontEnd
#MiniProject6-TweetApp-FrontEnd.
MicroServices CaseStudy Tweet - Front End

Continuing our micro services journey our task is now to create a front end for the application. You can use whatever technology you wish(Angular, React or Vue) or basic HTML, CSS & JS would also do. Feel free to experiment with the design.

Create webpages similar to the images shown below.

Please follow these instruction carefully to evaluate your code.

1. Create three pages - login.html, register.html and index.html, if you have used angular, react or vue build them into static files.
2. Copy all the static files into the folder "static-assets", a sample directory structure is shown below
static-assets/
index.html
-login.htm/
register.html
CSS/
3. Define the below listed functionalities.
register.html
create a form with id 'registration-form' and define three input fields inside it with name field as 'fullname', 'username', 'password' and a register button.
the form should submit to url 'http://localhost:8080/register' along with the registration details.
login.html

create a form with id 'login-form' and define two input fields inside it with name field as 'username', 'password' and a login button.
the form should submit to url 'http://localhost:8080/login' along with the login details.
index.html

create a homepage for the user like the one shown here, it should have a input textbox to write tweet and tweet button. Define a div where you fetch and display all the posts for the current user.

Get the posts from the url: http://localhost:8080/dbrestapi/getposts the posts format will be same as what you have defined in the dbrestapi micro app The posts should load automatically when the page loads.
index.html

in the homepage define a input search box with id search-input and a button with id search-button on clicking search button make a post request

to http://localhost:8080/dbrestapi/searchuser with post body containing the field serachText which is the text from the input box.

The post request will return a response containing the list of users. matching the search the format will be same as you defined in the dbrestapi micro app. Display all the contents of the post response as shown in image in a div with id search- container



