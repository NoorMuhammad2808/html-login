<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Login Page</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <div class="login-container">
        <h1>Login</h1>
        <form >
            <input type="text" name="username" placeholder="Username" required>
            <input type="password" name="password" placeholder="Password" required>
            <div class="remember-me">
                
                <label for="remember">Remember Me</label>
                <input type="checkbox" name="remember" id="remember">
            </div>
            <button type="submit">Login</button>
            <button type="submit" >Sign Up</button>
        </form>
        
    </div>
</body>
</html>



(style.css).............:

body {
   
    font-family: Arial, sans-serif;
    background-color: #f2f2f2;
    margin: 0 auto;
    padding: 0;
    display: flex;
    justify-content: center;
    align-items: center;
    height: 100vh;
}
.login-container {
    background-image: url("/bbbb.jpeg ");
    background-size: cover;
    background-position: center     ;
   padding: 20px;
    border-radius: 8px;
    box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
    width: 300px;
    text-align: center;
}
.login-container h1 {
    color: azure;
    text-shadow: 2px 2px 4px  black;
    margin-bottom: 20px;
    font-size: 24px;    
}
.login-container input[type="text"], 
.login-container input[type="password"] {
    width: 100%;
    padding: 10px;
    margin: 10px 0;
    border: 1px solid #ccc;
    border-radius: 4px;
}

.login-container button {
    width: 100%;
    padding: 10px;
    background-color: blue;
    border: none;
    color: white;
    font-size: 16px;
    border-radius: 4px;
    cursor: pointer;
    margin-top: 10px;
}


.remember-me {
    color: whitesmoke;
    display: flex;
    align-items: center;
    justify-content: start;
    margin: 10px 0;
}




