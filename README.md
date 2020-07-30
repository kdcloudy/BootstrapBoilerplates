# BootstrapBoilerplates
Quick and basic starters code for basic static layouts in HTML/CSS such as signup forms, grids, gradients using Bootstrap. This is for delivering a quick testable, clean UI while you can still focus on your backend and before you jump to React or Vue.

## Dependencies:
`link rel="stylesheet" href="https://fonts.googleapis.com/css?family=Roboto:300,400,500,700&display=swap"
link href="https://cdnjs.cloudflare.com/ajax/libs/twitter-bootstrap/4.5.0/css/bootstrap.min.css" rel="stylesheet"`

### A Login Jumbotron card
CSS:
```
.basic-card{
    height: 90%;
    width: 60%;
    position: absolute;
    top: 65%;
    left: 50%;
    padding:1%;
    transform: translate(-50%, -50%);
    border-radius: 10px 10px;
    background: #e0e5ec;
    display: flex;
    justify-content: center; 
}
```

### Gradients
CSS:
(Add this to any class or body for full gradient background)
 
 `background-image: linear-gradient(to bottom right, #2EC866, #0E141E);`
 
### Gradient Text
CSS:

```
#gradtext{
    background: linear-gradient(to bottom right, #E73C7E, #EE7752);
    -webkit-background-clip: text;
    -webkit-text-fill-color: transparent;

}
```


### Basic Dark Navbar:
HTML:
``` 
<!-- Navbar -->
<nav class="navbar fixed-top navbar-expand-lg navbar-dark bg-dark scrolling-navbar">
          <div class="container">
    
            <!-- Brand -->
            <a class="navbar-brand" href="/">
              <img src="#" height="60" width="200" alt="">
            </a>
    
            <!-- Links -->
            <div class="collapse navbar-collapse" id="navbarSupportedContent">
    
              <!-- Left -->
              <ul class="navbar-nav mr-auto">
                <li class="nav-item">
                  <a class="nav-link" href="#">Home</a>
                </li>
                <li class="nav-item">
                  <a class="nav-link" href="#">Explore</a>
                </li>
                <li class="nav-item">
                  <a class="nav-link" href="#">Download</a>
                </li>
            
              </ul>
    
              <!-- Right -->
              <ul class="navbar-nav nav-flex-icons">
              
                <li class="nav-item">
                  <a class="nav-link" href="#" target="_blank">Login</a>
                </li>
                <li class="nav-item">
                  <a class="nav-link" href="#" target="_blank">Sign Up</a>
                </li>
               
              
              </ul>
            </div>
          </div>
        </nav>
```
     
### Neumorphic UI:

```
body{
    background: #e0e5ec;
}


.neu-components{
    box-shadow: 9px 9px 16px rgb(163, 177, 198, 0.6),
    -9px -9px 16px rgba(255, 255, 255, 0.5);
    border: 0;
    background: #e0e5ec;
    border-radius: 10px;
    padding: 10px;
}
```

### Basic Sign up Form

```
 <form class="form-container" action="#">
                            <p class="h4 mb-4 text-center">Sign Up</p>
                            
                            <input type="text" name="name" id="defaultLoginFormtext" class="form-control mb-4" placeholder="Your name" required>
                            <input type="text" name="username" id="defaultLoginFormtext" class="form-control mb-4" placeholder="E-Mail" required>
                            <input type="password" name="password" id="defaultLoginFormPassword" class="form-control mb-4" placeholder="Password" required>
                            <label for="sel1">Gender:</label>
                            <div class="radio">
                              <label><input type="radio" name="optradio" checked>Male</label>
                            </div>
                            <div class="radio">
                              <label><input type="radio" name="optradio">Female</label>
                            </div>
                            <div class="radio disabled">
                              <label><input type="radio" name="optradio" disabled>Prefer not to say</label>
                          
                            </div>
                            <div class="form-group">
                                <label for="sel1">Select Difficulty Level</label>
                                <select class="form-control" id="sel1">
                                  <option>Beginner</option>
                                  <option>Intermediate</option>
                                  <option>Pro</option>
                                </select>
                              </div>

                             
                              <label for="birthday">Birthday:</label>
                              <input type="date" id="birthday" name="birthday" class="form-control mb-4">
                            

                              <div class="checkbox">
                                <label><input type="checkbox" value="">Enroll me part of the newsletter</label>
                              </div>
                              <div class="checkbox">
                                <label><input type="checkbox" value="">I accept to the terms of the end user license agreement.</label>
                              </div>
                              
                            <button class="btn btn-info btn-black btn-block my-4" type="submit">Create Account</button>
                            <button class="btn btn-info btn-red btn-block my-4" type="reset">Reset</button>
                        
                            <div class="text-center">
                                <p>Already a member?
                                    <a href="/login">Login now</a>
                                </p>
                        </form>
```



### Bootstrap Grid Sample:
Two columns taking 6 units, one row.
```
<div class="row">
  <div class="col-6">
    <div class="grid">
       <div class="content">
    <!-- <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod
      tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam,
      quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo.</p> -->
    </div>
    </div>
  </div>
  <div class="col-6">
    <div class="content">
    <!-- <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod
      tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam,
      quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo.</p> -->
    </div>
   </div>
 </div>
 ```
