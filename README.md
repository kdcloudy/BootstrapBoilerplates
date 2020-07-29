# BootstrapBoilerplates
Quick and basic starters code for basic static layouts in HTML/CSS such as signup forms, grids, gradients using Bootstrap.

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

`
#gradtext{
    background: linear-gradient(to bottom right, #E73C7E, #EE7752);
    -webkit-background-clip: text;
    -webkit-text-fill-color: transparent;

}
`


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
