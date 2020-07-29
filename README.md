# BootstrapBoilerplates
Quick and basic starters code for basic static layouts in HTML/CSS such as signup forms, grids, gradients using Bootstrap.

## Dependencies:
`link rel="stylesheet" href="https://fonts.googleapis.com/css?family=Roboto:300,400,500,700&display=swap"
link href="https://cdnjs.cloudflare.com/ajax/libs/twitter-bootstrap/4.5.0/css/bootstrap.min.css" rel="stylesheet"`

### A Login Jumbotron card

CSS Class:
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

HTML:
 `<div class="basic-card>
 <!--INSERT COMPONENTS HERE--->
 </div>'
 
 ### Gradients
 
 CSS:
 (Add this to any class or body for full gradient background)
 
 `background-image: linear-gradient(to bottom right, #2EC866, #0E141E);`


### Navbar:

` <!-- Navbar -->
        <nav class="navbar fixed-top navbar-expand-lg navbar-dark bg-dark scrolling-navbar">
          <div class="container">
    
            <!-- Brand -->
            <a class="navbar-brand" href="/">
              <img src="#" height="60" width="200" alt="">
            </a>
    
            <!-- Collapse -->
            <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarSupportedContent"
              aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
              <span class="navbar-toggler-icon"></span>
            </button>
    
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
    `
