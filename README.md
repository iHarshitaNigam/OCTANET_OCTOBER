# OCTANET_OCTOBER

//INDEX.HTML

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Landing page using html css</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
    <nav>
<div class="logo">
FaiStore
</div>
<div class="menu">
    <a href="#">Home</a>
    <a href="#">Blog</a>
    <a href="#">Search Products</a>
    <a href="#">Reviews</a>
    <a href="#">Contact</a>

</div>
<div class="register">
    <a href="#">Register</a>
</div>
</nav>
<section  class="h-text">
    <span>Enjoy</span>
    <h1>Fall is Here!</h1>
    <br>
    <a href="#">Go for Shopping</a>
</section>
    </header>
</body>
</html>

//STYLE.CSS

*{
    padding: 0;
    margin: 0;
    box-sizing: border-box;
}
header{
    width: 100%;
    height: 100vh;
    background:linear-gradient(rgba(0,0,0,0.8),rgba(0,0,0,0.2)) , url(fa.jpg);
    background-size: cover;
    font-family: 'Poppins',sans-serif;
}
nav{
    width: 100%;
    height: 100px;
  
    color: #fff;
    display: flex;
    justify-content: space-around;
align-items: center;
}
.logo{
    font-size: 2em;
    letter-spacing: 2px;
}
.menu a{
    text-decoration: none;
    color: #fff;
    padding: 10px 20px;
    font-size: 20px;
}

.menu a:hover{
   border: 1px solid indianred;
   background: transparent;
}
.register a{
    text-decoration: none;
    color: #fff;
    padding: 10px 20px;
    font-size: 20px;
    border-radius: 8px;
    background: indianred;
}
.register a:hover{
    border: 1px solid indianred;
    background: transparent;
}
.h-text{
    position: absolute;
    top: 50%;
    left: 50%;
    max-width: 650px;
    transform: translate(-50%,-50%);
    text-align: center;
    color: #fff;
}
.h-text span{
    letter-spacing: 5px;
}
.h-text h1{
    font-size: 3.5em;
}
.h-text a{
    text-decoration: none;
    background: indianred;
    padding: 10px 20px;
    color: #fff;
    letter-spacing: 5px;
    transition: 0.4s;
}
.h-text a:hover{
    border: 1px solid indianred;
    background: transparent;
}
