<template>
<div class="container">
    <div class="header1">
        <div id="img3" class="header1">
            <img src="left-logo.png" id="img3s" height="37" width="35"/>
        </div>
                <div id="searcharea" class="header1 input-container">
                        <input placeholder="search fro people, place and things" type="text" id="searchbox"/>
                        <i class="fa fa-search fa-lg fa-fw" aria-hidden="true"></i>
                        <div id="menu">
                                <ul>
                                        <li><a href="home"><b style="color:#d02d76">Home</b></a></li>
                                        <li><a href="group">Group</a></li>
                                        <li><a href="message">Message</a></li>
                                        <li><a href="notification">Notification</a></li>
                                        <li><a href=""><i class="fa fa-gear fa-lg fa-fw" aria-hidden="true"></i></a></li>
                                        <span id="nam">Syed Zeeshan Hasmi</span>
                                </ul>  
                                
                        </div>
            <div class="picture"> 
            <img src="jison.jpg"   alt="image not found" height="35" width="35">
        </div>
        <div class="col-sm-2 picture1">
            <div class="picture2">
                <img src="jison.jpg"   alt="image not found" height="151" width="151">
                <center>
                <h6 style="font-size:12px">Syed Zeeshan Hasmi</h6>
                <h6 style="font-size:12px">szhasmi1996@gmail.com</h6>
                <h6 style="font-size:12px">7462358211</h6>
                </center>
            </div>
        </div>

        <div class="col-sm-6 picture4">
            <div class="picture2">
                <img src="addsec.jpg"   alt="image not found" height="150" width="215">
                <center>
                <h6 style="font-size:12px">CABINE Areeba</h6>
                <h6 style="font-size:12px">Here goes out first advertisement</h6>
                </center>
            </div>
        </div>
        
         <div class="col-sm-6 picture5">
            <div class="picture2">
                <img src="addsec.jpg"   alt="image not found" height="150" width="215">
                <center>
                <h6 style="font-size:12px">IKARI KASPA KEMST</h6>
                <h6 style="font-size:12px">Here goes out second advertisement</h6>
                </center>
            </div>
        </div>
           

        <div class="col-sm-6 picture3">
           <P>Mr. Abc</P>
           <p>Mr. Xyz</p>
        </div>
    </div>    
</div>
           

</div>
</template>

<style>
body{background: whitesmoke;}
h6
{
    padding:-0px;
}
.picture4
{
    width: 245px;
    height: 230px;
    color:#B1B1AE;
    border-radius:3%;
    margin: 100px auto;
    overflow: hidden;
    transition: all 0.2s;
   -webkit-transition: all 0.2s;
    background:white;
    margin-top: -70px;
    margin-left:570px;
    padding-top: 14px;
}
.picture5
{
    width: 245px;
    height: 230px;
    color:#B1B1AE;
    border-radius:3%;
    margin: 100px auto;
    overflow: hidden;
    transition: all 0.2s;
   -webkit-transition: all 0.2s;
    background:white;
    margin-top: -90px;
    margin-left:570px;
    padding-top: 14px;
}
.picture{
    width: 45px;
    height: 45px;
    color: #FFFFFF;
    border-radius:5%;
    margin: 100px auto;
    overflow: hidden;
    transition: all 0.2s;
   -webkit-transition: all 0.2s;
    margin-top:-30px;
    margin-left: 450px;
}
.picture1{
    width: 184px;
    height: 243px;
    color:#B1B1AE;
    border-radius:3%;
    margin: 100px auto;
    overflow: hidden;
    transition: all 0.2s;
   -webkit-transition: all 0.2s;
    background:white;
    margin-top: -70px;
    margin-left:-160px;
    padding-top: 14px;
}
.picture3{
    width: 258px;
    height: 550px;
    color:#B1B1AE;
    border-radius:1%;
    margin: 100px auto;
    overflow: hidden;
    transition: all 0.2s;
   -webkit-transition: all 0.2s;
    background:white;
    margin-left:850px;
    margin-top:-570px;
    padding-top: 14px;
}
#nam
{
    margin-left:-565px;
    margin-top:50px;
}
/********menu css start*****/
#menu {
    width: 550px;
    height: 35px;
    font-size: 14px;
    font-family: Tahoma, Geneva, sans-serif;
    float: right;
    margin-right:150px;
    margin-top:-2px;
}
#menu ul {
    height: auto;
    padding: 8px 0px;
    margin: 0px;
}
#menu li { 
display: inline; 
padding: 10px; 
}
#menu a {
    text-decoration: none;
    color:white;
padding: 8px 8px 8px 8px;
    
}
#menu a:hover {
    color:#d02d76;
}
#menu i
{
margin-left:650px;
}
/*******menu css end*******/
#img3s
{
margin-left:100px;
margin-top: 15px;
}

.input-container i {
  position: absolute;
  left:355px;
  top: 4px;
  padding: 5px 15px;
  color: #aaa;
  height: 13px;
  width: 13px;
}

.header1{
position:fixed;
width:1366px;
height:60px;
background: black;
top:0;
left:0;
color:white;
z-index:7;
}
#searchbox
{
width:400px;
height:30px;
background:white;
padding:5px;
outline:none;
background-position:465px;
background-repeat:no-repeat;
color: black;
}
#searcharea{top:17px;
left:240px;
height:40px;
}
</style>
