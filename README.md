<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>3mly1</title>

    <link rel="stylesheet" href="test1.css">

    <style>
h1
{
    text-align: center;
    color: white;
    font-size: 45px;
    font-style: bold;
    font-family: Georgia, 'Times New Roman', Times, serif;
}

body
{
    font-family: Arial, Helvetica, sans-serif;
    background-color: rgb(27, 27, 27);
}

img.avatar
{
    width: 30%;
    border-radius: 50%;
    margin-top: 15px;
}

.avatarcontainer
{
    text-align: center;
}

.container 
{
    padding: 16px;
}

input [type=password] , [type=uname] , [type=password]
{
    width: 100%;
    padding: 12px  20px;
    margin: 8px -1px;
    border: 1px solid gray;
    border-radius: 7px;
}

button
{
    color: white;
    background-color: #04AA6D;
    padding: 14px 20px;
    margin: 9px;
    width: 47%;
    border-radius: 7px;
}

button:hover
{
    opacity: 50%;
    
}

.fieldset{
    border-radius: 50px;
    color:white;
    padding: 55px;
    margin: 50px;
    padding-bottom: 10px;    
    padding-top: 10px;
    position: sticky;
}

.cancel
{
    background-color: red;
    width: 100px;
    color: white;
}

.forgot
{
    float: right;
}

    </style>

<body>
    <img src="urlfile:///C:/Users/Peter/Desktop/Picture1.png" alt="">
    <h1> <strong><u>Modern Academy</u></strong></h1>

    <fieldset class="fieldset">
    <form action="loginform" class="form">
        
        <div class="avatarcontainer">
        <img src="file:///C:/Users/Peter/Desktop/Downloads/22-223941_transparent-avatar-png-male-avatar-icon-transparent-png.png" alt="avatar" class="avatar">
        </div>

        <div class="container">
        <label for="uname"><b> Username<b></label><br>
        <input type="uname" placeholder="Enter Username" name="uname" required><br>

        <label for="password"><b>Password<b></label><br>
        <input type="password" placeholder="Enter Password" name="password" required><br>
        
        <div class="button1">
        <button type="submit">Login</button>
        <button type="submit">Sign Up</button><br>
        </div>

        </div>
        
        
        <label for="checkbox"> 
            <input type="checkbox" name="checkbox" checked> Remember me
        
        </label>

        <a class="forgot" href="http://ggggg.com" target="_blank" rel="noopener noreferrer">Forgot password</a> <br>

        <button type="button" class="cancel"> Cancel</button>
        

    </fieldset>
    </form>
</body>
</html>
