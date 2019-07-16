
<html>
<head>
<title> Log in form design</title>
<style type="text/css">
body
{
margin:0;
padding:0;
background:#000;
background-size:cover;
background-position:center;
font-family:sans-serif;
}
.loginbox{
height:420px;
width:320px;
background:#000;
color:#fff;
top:50%;
left:50%;
right:50%;
position:absolute;
transform:translate(-50%,-50%);
box-sizing:border-box;
padding:70px 30px;
}

.images{
height:100px;
width:100px;
border-radius:50%;
position:absolute;
top:-13%;
left:calc(50% - 50px);
}
h1{
margin-bottom:30px;
padding:0px;
text-align:center;
font-size:22px;
}
.loginbox p{
margin:0;
padding:0;
font-weight:bold;
}
.loginbox input{
width:100%;
margin-bottom:20px;
}
.loginbox input[type="text"],input[type="password"]
{
border:none;
border-bottom:1px solid #fff;
background:transparent;
outline:none;
height:40px;
color:#fff;
font-size:15px;
}
.loginbox input[type="submit"]
{
border:none;
outline:none;
background:#F44336;
height:40px;
font-size:20px;
color:#fff;
border-radius:20px;
font-weight:bold;
}
.loginbox input[type="submit"]:hover
{
background:#ffc109;
color:#000;
}
.loginbox a
{
text-decoration:none;
color:#fff;
font-size:12px;
line-height:20px;
color:darkgrey;
}
.loginbox a:hover
{
color:#ffc107;
}
</style>
</head>
<body>
<div class="loginbox">
<img src="login.jpg" class="images">
<h1>Login Here</h1>
<p>Username</p>
<input type="text" name="" placeholder="Enter Username">
<p>Password</p>
<input type="password" name="" placeholder="Enter the password">
<input type="Submit" Name="" value="Login">
<a href="#">Lost your password?</a><br>
<a href="#" >Don’t have an account?</a>
</div>
</body>
</html>