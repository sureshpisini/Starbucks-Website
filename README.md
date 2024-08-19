<!DOCTYPE html>
<html lang="en">
<head>
    <link rel="stylesheet" href="index.CSS">
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-QWTKZyjpPEjISv5WaRU9OFeRpok6YctnYmDr5pNlyT2bRjXh0JMhjY6hW+ALEwIH" crossorigin="anonymous">
</head>
<body>
    <div class="bg-container">
    <nav class="navbar navbar-expand-lg navbar-light " >
        <img src="SB Logo.jpg" style="margin-bottom:10px; width:8vw; height:12vh; border-radius: 10px;">
       
        <div class="collapse navbar-collapse" id="navbarNavDropdown" style="justify-content: right;">
            <a class="navbar-brand" id="home1" href="#">Home</a>
            <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarNavDropdown" aria-controls="navbarNavDropdown" aria-expanded="false" aria-label="Toggle navigation">
              <span class="navbar-toggler-icon"></span>
            </button>
          <ul class="navbar-nav">
            <li class="nav-item active">
              <a class="nav-link" id="home1" href="#">Menu</a>
            </li>
            <li class="nav-item home">
              <a class="nav-link" id="home1"  href="#">About</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" id="home1" href="#">Contact</a>
            </li>
            
          </ul>
        </div>
      </nav>
    </div>
    <div class="bg-container1">
        <h1 class="head">FREE COFFEE</h1>
        <h2 class="head">IS A </h2>
        <h3 class="head"> TAP AWAY </h3>
        <button class="button">Join Now</button>
    </div>
</body>
</html>


.bg-container{
    height:15vh;
    background-color: black;

}
#home1{
    color:white;
    margin-right: 35px;
}
.bg-container1{
    background-image: url("SB Logo.jpg");
    background-size: cover;
    width:100vw;
    height:85vh;
    padding:70px;
}
.head{
    color:white;
    font-style: oblique;

}
.button{
    background-color: green;
    border-radius: 10px;
    padding: 10px;
    margin: 10px;
    font-style: italic;
    font-size: medium;
}
