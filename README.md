<!DOCTYPE html>
<html lang="en">
<head>
<style>
    .block{
    height:745px;
    width:100%;
    background-color:rgb(248, 234, 208);
    display:flex;
    flex-direction: column;
    justify-content: center;
    padding: 10px;
}
.container1{
height:60px;
width:1300px;
font-size:17px;
border-radius: 40px;
background: white;
display:block;
margin:auto;
margin-top: 7px;
color:black;
display: flex;
padding: 10px;
}
.img{
    height:50px;
    width:170px;
    border-radius:20px;
    margin:10px;
    text-align: center;
    align-items: center; 
}
.fimg{
    height:30px;
    width:130px;
    margin:2px;
}
.prod{
     height:50px;
    width:90px;
    font-size: large;
    text-align: center;
}
.abc{
    height:50px;
    width:100px;
    font-size: large;
    text-align: center;

}
.Signin_btn1{
   height:50px;
   width:50px;
   font-size:20px;
   border-radius: 20px;
   border:2px solid white;
   background: white;
   display:block;
   color:white;

}
.btn1{
    display: inline;
    margin: 10%;
    height: 40px;
    width: 90px;
    border-radius:5px;
    border-color: white;
    background-color: white;
    font-size:medium;
}
.space{
    height:50px;
    width:20px;
}
.btn2{
    display: block;
    margin:5%;
    border-radius:5px;
    border-color: purple;
    height: 40px;
    width: 170px;
    color: purple;
    align-items: center;
    background-color: white;
} 
.btn3{
    display: block;
    margin:5%;
    border-radius:5px;
    border-color: purple;
    height: 40px;
    width: 170px;
    color: white;
    align-items: center;
    background-color: purple;
} 
.container2{
    height:630px;
    width:100%;
    display: flex;
    align-content: flex-end;
}   
.left{
height:350px;
width:40%;
font-size:17px;
background:rgb(133, 187, 234);
border-top-right-radius: 170px;
border-bottom-right-radius: 170px;
display:block;
color:black;
margin-top: 20px;
margin-left: 10%;
margin-right: 10%;


}
.right{
height:150px;
width:40%;
font-size:17px;
background:none;
display:block;
color:black;
margin:50px;
}
.text{
    line-height: 20px;
    font-size: larger;
}
.link{
    color: blue;
}
.container3{
    height:300px;
    width:100%;
    display: flex;
    align-content: flex-end;
}
.left2{
    width:60%;
    margin:5%;
    font-size: larger;
    line-height: 20px;
}
.right2{
height:200px;
width:60%;
font-size:17px;
background:green;
border-top-left-radius: 200px;

display:block;
color:black;
margin-top: 20px;
margin-left: 10%;
margin-right: 10%;
}
</style>
</head>
<body>
    <div class="block">
        <div class="container1">
            <div class="img">
                <img src="slackimage.png" class="fimg">
            </div class="prod">
             <label for="products"></label>
             <select name="products" id="products">
            <option value="Products"><b>Products</b></option>
             <option value="Features">Features</option>
             <option value="Channels">Channels</option>
             <option value="Integrations">Integrations</option>
             <option value="security">Security</option>
             <option value="slack connect">Slack connect</option>
             <option value="Customers">Customers</option>
            </select>
            
            <div class="abc"><p><b>Solutions</b></p></div>
            <div class="abc"><p><b>Enterprise</b></p></div>
            <div class="abc"><p><b>Resources</b></p></div>
            <div class="abc"><p><b>Pricing</b></p></div>
            <div class="abc"><p></p></div>
            
            
            <div class="Sign_Btn1">
                 <button class="btn1">Sign in</button>
            </div>
            <div class="space"><p></p></div>
            <div class="Sign_Btn1">
                <button class="btn2">TALK TO SALES</button>
            </div>
            <div class="space"><p></p></div>
            <div class="Sign_Btn1">
                <button class="btn3">TRY FOR FREE</button>
            </div>
            
        </div>
        <div class="container2">
            <div class="left"></div>
            <div class="right">
                <div class="text">
                    <h1><br>Bring your team </h1>
                    <h1>together</h1>
                    <p>At the heart of Slack are channels:originated spaces for<br>
                    everyone and everything that you need for work.In<br>
                    channels,it's easier to connect across departments,offices,<br>
                time zones and even other companies.</p>
                <p class="link">Learn more about channels-</p>
                </div>
                
            </div>
        
    </div>
    <div class="container3">
        <div class="left2">
        <h1>Choose how you<br><br>want to work</h1>
        </div>
        <div class="right2"></div>
    </div>
        
    </div>
</body>
