<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Home page</title>
</head>
<style>
    body{
        background-color: rgb(255, 255, 255);
    }
.bar {
    position: absolute;
    top: 0px;
    width: 1538px;
    height: 50px;
    left: -10px;
    background-color: cadetblue;
}
.bar .title{
    text-decoration: none;
    font-size: 25px;
    text-transform: uppercase;
    color: white;
    font-weight: bold;
    left: 50px;
    position: absolute;
    top: 7px;
    font-family: Verdana, Geneva, Tahoma, sans-serif;
}
.bar .button{
    font-family: Verdana, Geneva, Tahoma, sans-serif;
    position: relative;
    color: white;
    display: inline-block;
    text-align: center;
    left: 900px;
    top: -2px;
    margin-right: 20px;
    margin-left: 20px;
    font-weight: bold;
    font-size: 18px;
    padding: 15px ;
    border-radius: 10px;
    transition-property: transform;
    transition-timing-function: ease-in-out;
    transition-duration: 0.3s;
    text-decoration: none;
}
.button:hover{
    transform: translateY(-7px);
}
.heading{
    position: relative;
    text-transform: uppercase;
    color: darkcyan;
    text-align: center;
    top:220px;
    text-transform: bolder;
    font-family:Georgia, 'Times New Roman', Times, serif;
    font-size: 70px;
}
.text{
    position: relative;
    color: rgb(0, 0, 0);
    text-align: center;
    top:260px;
    font-size: 50px;
    font-family: 'Times New Roman', Times, serif;
    font-weight: lighter;
}
</style>
<body>
    <div class="bar">
        <div class="title">hquan</div>
        <a href="index.html" class="button">Home</a>
        <a href="profile.html" class="button">CV</a>
        <a href="fishtank.html" class="button">Fish-tank</a>
    </div>
    <div class="heading">Welcome to Hquan page!</div>
    <div class="text">You can find my project above :D</div>
</body>
</html>
