# Ex-10-BOOTSTRAP
NAME: MYTHILI V
DEPT: CSE
REG NO:212223040123

EX-10(1):

AIM:

Create a Responsive feedback form for a virtual workshop on Constructing Modern Websites built with Bootstrap.

DESIGN STEPS:10(1) :

STEP 1:

Initialize the HTML document.

STEP 2:

Create the body structure.

STEP 3:

Construct the form

STEP 4:

Add a submit button and Link Bootstrap JavaScript.

CODE 10(1) :
```
<html>
    <head>
        <title>Feedback Form | Virtual Workshop on constructing Modern Websites</title>
        <link rel="stylesheet" herf="style.css">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
    </head>
    <body>
        <div class="container">
            <div class="title">Feedback</div>
            <div class="content">
                <form action="#">
                    <div class="user-details">

                        <div class="input-box">
                            <span class="details">First Name</span>
                            <input type="text" placeholder="Enter your 1 st name" required>
                        </div>

                        <div class="input-box">
                            <span class="details">Last Name</span>
                            <input type="text" placeholder="Enter your last name" required>
                        </div>

                        <div class="input-box">
                            <span class="details">Email</span>
                            <input type="text" placeholder="Enter your email" required>
                        </div>

                        <div class="input-box">
                            <span class="details">Phone Number</span>
                            <input type="text" placeholder="Enter your number" required>
                        </div>
                    </div>

                    <div class="rating-details">
                        <input type="radio" name="rate" id="dot-1">
                        <input type="radio" name="rate" id="dot-2">
                        <input type="radio" name="rate" id="dot-3">
                        <input type="radio" name="rate" id="dot-4">
                        <input type="radio" name="rate" id="dot-5">
                        <span class="rate-title">Rating</span>

                        <div class="category">
                            <label for="dot-1">
                                <span class="dot one"></span>
                                <span class="rate">1</span>
                            </label>

                            <label for="dot-2">
                                <span class="dot tow"></span>
                                <span class="rate">2</span>
                            </label>

                            <label for="dot-3">
                                <span class="dot three"></span>
                                <span class="rate">3</span>
                            </label>

                            <label for="dot-4">
                                <span class="dot four"></span>
                                <span class="rate">4</span>
                            </label>

                            <label for="dot-5">
                                <span class="dot five"></span>
                                <span class="rate">5</span> 
                            </label>

                        </div>
                    </div>
                    <div class="button">
                        <input type="submit" value="Post">
                    </div> 
                </form>
            </div>
        </div>
    </body>
</html>
```

OUTPUT 10(1):

![modernweb](https://github.com/Mythili7339267708/ODD2023-WT-Ex-10-BOOTSTRAP/assets/144260246/3b85559c-2391-48ab-be89-2e3439f77395)

RESULT:

This code creates a responsive feedback form for a virtual workshop on constructing modern websites built with Bootstrap.

EX-10(2):

AIM:

Create a Responsive student registration form for ABC Engineering College built with Bootstrap.

DESIGN STEPS 10(2):

STEP 1:

Initialize the HTML document with the necessary Bootstrap links.

STEP 2:

Create a container for the form and add a heading.

STEP 3:

Inside the form, create form groups for the student’s name, email, and course.

STEP 4:

Add a submit button for the form.

STEP 5:

Link the Bootstrap JavaScript file at the end of the body.

CODE:10(2):
```
<html>
    <head>
         <title>Student Registration Form | ABC Engineering College</title>
         <link rel="stylesheet" herf="style.css">
         <meta name="viewport" content="width=device-width, initial-scale=1.0">
    </head>
    <body>
        <div class="container">
            <div class="title">Registration</div>
            <div class="content">
              <form action="#">
                <div class="user-details">
                 
         <div class="input-box">
                    <span class="details">First Name</span>
                    <input type="text" placeholder="Enter your 1st name" required>
                    </div>
        
        <div class="input-box">
                    <span class="details">Last Name</span>
                    <input type="text" placeholder="Enter your last name" required>
                    </div>
        
                  <div class="input-box">
                    <span class="details">Username</span>
                    <input type="text" placeholder="Enter your username" required>
                  </div>
        
                  <div class="input-box">
                    <span class="details">Email</span>
                    <input type="text" placeholder="Enter your email" required>
                  </div>
        
                  <div class="input-box">
                    <span class="details">Phone Number</span>
                    <input type="text" placeholder="Enter your number" required>
                  </div>
        
                  <div class="input-box">
                    <span class="details">Password</span>
                    <input type="text" placeholder="Enter your password" required>
                  </div>
                  <div class="input-box">
                    <span class="details">Confirm Password</span>
                    <input type="text" placeholder="Confirm your password" required>
                  </div>
                </div>
                <div class="gender-details">
                  <input type="radio" name="gender" id="dot-1">
                  <input type="radio" name="gender" id="dot-2">
                  <input type="radio" name="gender" id="dot-3">
                  <span class="gender-title">Gender</span>
        
                  <div class="category">
                    <label for="dot-1">
                    <span class="dot one"></span>
                    <span class="gender">Male</span>
                  </label>
        
                  <label for="dot-2">
                    <span class="dot two"></span>
                    <span class="gender">Female</span>
                  </label>
        
                  <label for="dot-3">
                    <span class="dot three"></span>
                    <span class="gender">Prefer not to say</span>
                    </label>
        
                  </div>
                </div>
                <div class="button">
                  <input type="submit" value="Register">
                </div>
              </form>
            </div>
          </div>
        
    </body>
</html>
```
OUTPUT 10(2):

<img width="960" alt="studentreg" src="https://github.com/Mythili7339267708/ODD2023-WT-Ex-10-BOOTSTRAP/assets/144260246/1bfea639-1e42-4c99-b88b-c04e8af69484">

RESULT:

This code creates a Responsive student registration form for ABCEngineering College built with Bootstrap.

Ex-10(c)

AIM:

Develop a program to structure vertical form layouts which handle form validation in bootstrap.

DESIGN STEPS 10(3):

STEP 1:

Initialize the HTML document with the necessary Bootstrap links.

STEP 2:

Create a container for the form and add a heading.

STEP 3:

Inside the form, create a form group for the name input field. Add the required attribute to the input field for validation.

STEP 4:

Add a submit button for the form.

STEP 5:

Add a script to handle the form validation on submit.

CODE 10(3):
```
<form>
      <div class="form-group">
      <div class="col-md-6">
                  <label for="valid01" class="form-label">Username</label>
                  <input type="text" class="form-control" id="valid01" required>
                 <div class="invalid-feedback">
                       Please provide a valid Username.
                  </div>
            </div>
      <div class="col-md-3">
                  <label for="valid02" class="form-label">Password</label>
                  <input type="text" class="form-control" id="valid02" required>
                 <div class="invalid-feedback">
                       Please provide a valid Password.
                  </div>
            </div>
      <div class="col-md-3">
                  <label for="valid03" class="form-label">Department</label>
                  <select class="form-select" id="valid04" required>
                        <option>Choose anyone Department</option>
                        <option>AIML</option>
                        <option>AIDS</option>
                        <option>IOT</option>
                  </select>
                  <div class="invalid-feedback">
                        Please select a valid Department.
                  </div>
            </div>
      <div class="col-md-9">
                  <label for="valid04" class="form-label">Mobile Number</label>
                  <input type="text" class="form-control" id="valid04" required>
      <div class="valid-feedback">
                        Entered Details are correct.
                  </div>
            </div>
      <div class="col-md-9">
                  <label for="valid05" class="form-label">Designation</label>
                  <input type="text" class="form-control" id="valid05" required>
      <div class="valid-feedback">
                        Entered Details are correct.
                  </div>
            </div>
      <div class="col-md-9">
                  <label for="valid06" class="form-label">E-Mail ID</label>
                  <input type="text" class="form-control" id="valid06" required>
      <div class="valid-feedback"> Entered Details are correct.
                  </div>
            </div>
      <div class="col-md-3">
                  <label for="valid07" class="form-label">Term & Conditions </label>
                  <input type="checkbox" class="form-control" id="valid07" required>
      <div class="invalid-feedback">
                        You must agree to terms and conditions before submitting...
                  </div>
            </div>
      <button type="button" class="btn btn-success"> Submit </button>
      ```

    OUTPUT 10(3):
    

![stdverform](https://github.com/Mythili7339267708/ODD2023-WT-Ex-10-BOOTSTRAP/assets/144260246/bf340c64-bcbf-49f4-bc03-2a3df5f3cdf9)

RESULT:

This code develops a program to structure vertical form layouts which handle form validation in bootstrap.

Ex-10(4):

AIM:

Create a basic email login form in Bootstrap with validation function.

DESIGN STEPS: 10(4)

STEP 1:

Initialize the HTML document with the necessary Bootstrap links.

STEP 2:

Create a container for the form and add a heading.

STEP 3:

Inside the form, create a form group for the email input field. Add the required attribute to the input field for validation.

STEP 4:

Add a submit button for the form.

STEP 5:

Add a script to handle the form validation on submit.

CODE:10(4)
```
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Email Login Form</title>
  <link rel="stylesheet" herf="style.css">
</head>
<body>

<div class="container mt-5">
  <div class="row justify-content-center">
    <div class="col-md-6">
      <h2>Email Login</h2>
      <form id="loginForm">
        <div class="form-group">
          <label for="email">Email address</label>
          <input type="email" class="form-control" id="email" name="email" required>
          <div class="invalid-feedback">Please enter a valid email.</div>
        </div>
        <div class="form-group">
          <label for="password">Password</label>
          <input type="password" class="form-control" id="password" name="password" required>
        </div>
        <button type="submit" class="btn btn-primary">Login</button>
      </form>
    </div>
  </div>
</div>

<script src="https://code.jquery.com/jquery-3.5.1.slim.min.js"></script>
<script src="https://cdn.jsdelivr.net/npm/bootstrap@4.5.2/dist/js/bootstrap.bundle.min.js"></script>
<script>
  
  (function () {
    'use strict'

    var forms = document.querySelectorAll('.needs-validation')

    Array.prototype.slice.call(forms)
      .forEach(function (form) {
        form.addEventListener('submit', function (event) {
          if (!form.checkValidity()) {
            event.preventDefault()
            event.stopPropagation()
          }

          form.classList.add('was-validated')
        }, false)
      })
  })()
</script>

</body>
</html>
```
OUTPUT:10(4)
![email](https://github.com/Mythili7339267708/ODD2023-WT-Ex-10-BOOTSTRAP/assets/144260246/1b18ba40-7352-4997-81d0-c9fea2fca713)


RESULT:

This code creates a basic email login form in Bootstrap with validation function.
