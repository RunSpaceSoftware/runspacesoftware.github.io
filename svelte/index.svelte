<html lang="en">
<head>
    <link rel="stylesheet" href="">
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="icon" type="image/x-icon" href="favicon.ico">
    <title>Runspace</title>
</head>
<body class="body">
    <div>

    </div>
    <div class="topnav">
        <a class="active" href="index.svelte">Home</a>
        <a href="about.svelte">About</a>
        <a href="https://github.com/RunSpaceSoftware">Github</a>
        <a href="https://gamefarmer2.itch.io">ItchIo</a>
        <a href="https://twitter.com/AGameFarmer">Twitter</a>
        <a href="https://www.youtube.com/channel/UCcAK2RCGrgMnHBcoLv7KYLg">Youtube</a>
        <p>Shayan Farzaneh</p>
    </div>
    <div class="main">
        <h1>A blog for my research, experiment and projects</h1>
    </div>
    <div class="sub" onclick="location.href='#';" style="cursor: pointer;">
        <h3>Experiments</h3>
    </div>
    <div class="sub" onclick="location.href='#';" style="cursor: pointer;">
        <h3>Research</h3>
    </div>
    <div class="sub" onclick="location.href='#';" style="cursor: pointer;">
        <h3>Upcoming Projects</h3>
    </div>
    <div class="sub" onclick="location.href='#';" style="cursor: pointer;">
        <h3>Ongoing Projects</h3>
    </div>
    <div>
        <h1>_____________________________________________________________</h1>
        <h5>Copyright2023. RunSpaceSoftware.</h5>
    </div>
</body>
</html>

<style>
    .topnav {
    background-color: #333;
    overflow: hidden;
  }
  
  /* Style the links inside the navigation bar */
  .topnav a {
    float: left;
    color: #f2f2f2;
    text-align: center;
    padding: 14px 16px;
    text-decoration: none;
    font-size: 17px;
  }

  .topnav p {
     float: right;
     text-align: center;
     color: #f2f2f2;
     padding-right: 8px;
     text-decoration: none;
     font-size: 17px;
     font-family: 'Times New Roman', Times, serif;
  }
  
  /* Change the color of links on hover */
  .topnav a:hover {
    background-color: #ddd;
    color: black;
    
  }
  
  /* Add a color to the active/current link */
  .topnav a.active {
    background-color: aqua;
    color: black;
  }

.body {
    background-color: black;
}

.body div {
    color: #ddd;
    text-decoration: none;
    text-align: center;
    font-size: larger;
}

.sub {
  border-style: dotted;
  border-radius: 2px;
  padding: 10px;
  margin: 20px;
}

.sub:hover {
  background-color: aquamarine;
  color: black;
}
</style>