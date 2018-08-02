#<!DOCTYPE html>
<html>
  <head>
    <script src="myScripts.js"></script>
    <link rel="stylesheet" href="homepage.css">
    <script>
    function openNav() {
  document.getElementById("mySidenav").style.width = "250px";
}

function closeNav() {
  document.getElementById("mySidenav").style.width = "0";
}
  </script>
  </head>
  <body style= background-image:url(bluebooks4.jpg) no-repeat center center fixed;
        -webkit-background-size: cover;
        -moz-background-size: cover;
        -o-background-size: cover;
        background-size: cover;background-repeat:no-repeat;>
  <div id="mySidenav" class="sidenav">
    <a href="javascript:void(0)" class="closebtn" onclick="closeNav()">&times;</a>
    <a href="#">Find/Near Me</a>
    <a href="#">Add A Library</a>
    <a href="#">What's Trending?</a>
    <a href="#">Book Quiz!</a>
  <a href="#">About Us</a>
</div>

<span style="font-size:30px;cursor:pointer" onclick="openNav()">&#9776;</span>
<div class="lobsterfont">
  WELCOME
</div>

<div class= "afont">
  <span style="background-color: #f4c095; opacity: 0.7">  Hunt4Books was developed by girls who code graduates who are passionate about spreading oppertunies for education.This site helps locate little free librarys and other free books or book exchange locations. We belive that anyone can make a differece; so we implamented a page where you can add librarys you built or found!.
  </span>

</div>

</body>
</html>


#css starts here
body{
  background-color: #071e22
}
.lobsterfont {
  font-family: Lobster; font-size: 100px; font-style: bold; font-variant: normal; font-weight: 700; line-height: 26.4px;text-align: center; color: #f4c095; text-decoration: underline;
 }
.afont {
  font-family: "Gill Sans", "Gill Sans MT", Calibri, sans-serif; font-size: 20px; font-style: normal; font-variant: normal; font-weight: 600; line-height: 20px;text-align: center;  position:fixed; bottom: 350px;right: 0px; opacity: 1;color: #ee2e31;margin-top: 1px; margin-bottom: 0px; margin-right: 100px; margin-left: 80px;
}




.sidenav {
    height: 100%;
    width: 0;
    position: fixed;
    z-index: 1;
    top: 0;
    left: 0;
    background-color: #f4c095;
    overflow-x: hidden;
    transition: 0.5s;
    padding-top: 60px;
}

.sidenav a {
    padding: 8px 8px 8px 32px;
    text-decoration: none;
    font-size: 25px;
    color: #818181;
    display: block;
    transition: 0.5s;
    border-bottom: 2px solid #679289;
}

.sidenav a:hover {
    color: #f1f1f1;
}

.sidenav .closebtn {
    position: absolute;
    top: 0;
    right: 25px;
    font-size: 36px;
    margin-right: 50px;
}

@media screen and (max-height: 450px) {
  .sidenav {padding-top: 15px;}
  .sidenav a {font-size: 18px;}
}


