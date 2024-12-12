<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
   <div class="login">
    <div class="login2">
        <h1> Softerbind <br> <br> <br> Segurança de software <br/>Melhor do brasil</h1>
        <img src="security-animate.svg" class="img1" alt="segurity2.0">
    </div>
    <div class="login3">
        <div class="login4">
            <h1>Login</h1>
            <div class="text">
                <label for="login">login</label>
                <input type="text" id="login" placeholder="login">
            </div>
            <div class="text">
                <label for="senha">Senha</label>
                <input type="password" id="senha" placeholder="Senha">      
            </div>
            <button class="btn-login">login</button>
        </div>
    </div>
   </div>
</body>
</html>

style.css

body{
    margin: 0;
}

.login{
    width: 100vw;
    height: 100vh;
    background-color: rgb(68, 10, 10);
    display : flex;
    justify-content: center;
    align-items: center;
    font-size: 3vw;
}

.img1{
    width: 30vw;
}

.login2{
    width: 50vw;
    height: 100vh;
    display: flex;
    justify-content: center;
    align-items: center;
    flex-direction: column;
}

.login2 > h1{
    font-size: 3vw;
    color: #ffffff;
}

.login3{
    width: 50vw;   
    height: 100vh;
    display: flex;
    justify-content: center;
    align-items: center;
}

.login4{
    width: 60%;
    display: flex;
    justify-content: center;
    align-items: center;
    flex-direction: column;
    padding: 30px 35px;
    background: rgb(136, 33, 33);
    border-radius: 20px;
    box-shadow: 0px 10px 40px #9e6b6b56;
}

.login4 > h1{
    font-size: 2.5vw;
    color: #ffffff;
    margin: 0;
}

.text{
    font-size: 2vw;
    color: #ffffff;
    margin-bottom: 10px;
    margin-top: 10px;
    display: flex;
    flex-direction: column;
    justify-content: center;
    margin: 10px;
    width: 100%;
}

.text > input{
    width: 100%;
    padding: 10px;
    border: none;
    border-radius: 10px;
    background: #f1f1f1;
    font-size: 12pt;
    box-shadow: 0px 10px 40px #ffffff56;
    outline: none;
    box-sizing: border-box;
}

.text > label{
    color: #ffebeb;
    margin-bottom: 10px;
}

.text > input::placeholder{
    color: #000000;
}

.btn-login{
    width: 100%;
    padding: 16px 0px;
    margin: 25px;
    border: none;
    border-radius: 8px;
    background: #fffbfb;
    font-size: 12pt;
    box-shadow: 0px 10px 40px -12px #08080856;
    outline: none;
    box-sizing: border-box;
    cursor: pointer;
    text-transform: uppercase;
    font-weight: 800;
    cursor: pointer;;
}

@media screen and (max-width: 800px) {
    .login2 {
        font-size: 6vw;
    }
    
}

@media screen and (max-width: 600px) {
    .login{
        flex-direction: column;
    }
}


http://127.0.0.1:5500/index.html
