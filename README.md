# project1-nexus
Login and Signup Page-Frontend
To create a simple login and signup form with validation using HTML, CSS & JavaScript.

FORM STRUCTURE
      To create the form, we need to use the <form> tag. Login form is made up of three <input> elements, text field for the username, password field for the password and submit field for the login button. Other than these three elements, Signup form includes email field for the user email address. <input> tag does not have a closing tag.
                    <input type="text" name="name" id="logName" placeholder="Username">



STYLING
            <link rel="stylesheet" type="text/css" href="style.css">


            
ANIMATION
            <script src="index.js"></script>



include jquery CDN within the <script> tag.
            <script src="https://code.jquery.com/jquery-3.3.1.min.js"
            integrity="sha256-FgpCb/KJQlLNfOu91ta32o/NMZxltwRo8QtmkMRdAu8=" crossorigin="anonymous"></script>



VALIDATION
              <form class="login"name="loginForm" onsubmit="returnvalidateLoginForm()" method="POST">
