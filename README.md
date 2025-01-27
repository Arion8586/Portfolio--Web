# Portfolio--Web
This is my First Portfolio Website.
<br>
Himanshu sarsuniya
<br>
nav list
HTML Code
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Portfolio</title>
    <link rel="stylesheet" href="style.css">
</head>

<body>
    <div class="portfolio-container">
        <ul class="navlist">
            <li><a href="#">Home</a> </li>
            <li><a href="#">Work</a> </li>
            <li><a href="#">About</a> </li>
            <li><a href="#">Project</a> </li>
            <li><a href="#">Service</a> </li>
        </ul>
    </div>
</body>

</html>
CSS Code
@import url('https://fonts.googleapis.com/css2?family=Poppins:wght@500&display=swap');
*{
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    font-family: "Poppins", serif;
}
.portfolio-container{
    min-height: 100vh;
    width: 100%;
}
.navlist{
    display: flex;
    gap: 3.5rem;
    /* background-color: red; */
    height: 15vh;
    width: 100%;
    justify-content: center;
    align-items: center;
}
.navlist li{
    list-style: none;
}
.navlist li a{
    text-decoration: none;
    text-transform: uppercase;

}

