<!DOCTYPE html>
<html lang="es">
<head>
<meta http-equiv="Content-Type" content="text/html; charset=windows-1252">
<title>Mi sitio web</title>
<meta name="Description" content="Paginas donde encontrar contenido interesante">
<meta name="viewport" content="initial-scale=1.0, user-scalable=yes">
<meta name="Robots" content="index, follow">
<link href="style/estilo.css" rel="stylesheet" type="text/css" media="screen">
</head> 
<body>
<div id="inicio"></div>
<div id="header">
<?php    
    include "include/acklogo.png";   
?>
<div id="page">
<h1>GrupoACK S.A. DE C.V</h1>
<?php    
    include "include/acklogo.png";   
?>

<div class="intro">
Hola colega para tener acceso a los recursos en la nube de los que dispone la empresa ingresa con tu usuario y contraseña en el boton de abajo "ingresar"
</div>
Esta es la página principal o de inicio de mi sitio web.<br>
Es la primera que ven los que entran al sitio por primera vez y en todas las páginas restantes hay un enlace que conduce a ella.<br>
En ella puedo poner enlaces a las otras páginas, imágenes sugestivas, videos o cualquier otro elemento.<br>
<img style="margin:12px 0 12px 0;" src="img/acklogo.png" width="620" height="400" alt="Imagen para el intro" title="Mi sitio web, actualidad y tecnologia"><br>

<h2>Enlaces a mis artículos</h2>
<div class="enlaces">
<style>
form {
    border: 3px solid #f1f1f1;
}
input[type=text], input[type=password] {
    width: 70%;
    padding: 12px 10px;
    margin: 8px 0;
    display: inline-block;
    border: 1px solid #ccc;
    box-sizing: border-box;
}
button {
    background-color: #4CAF50;
    color: white;
    padding: 14px 20px;
    margin: 8px 0;
    border: none;
    cursor: pointer;
    width: 100%;
}
button:hover {
    opacity: 0.8;
}
.cancelbtn {
    width: auto;
    padding: 10px 18px;
    background-color: #f44336;
}
.imgcontainer {
    text-align: center;
    margin: 24px 0 12px 0;
}
img.avatar {
    width: 40%;
    border-radius: 50%;
}
.container {
    padding: 16px;
}
span.psw {
    float: right;
    padding-top: 16px;
}
/* Change styles for span and cancel button on extra small screens */
@media screen and (max-width: 300px) {
    span.psw {
       display: block;
       float: none;
    }
    .cancelbtn {
       width: 100%;
    }
}
</style>

<h2>Login Form</h2>

<form action="/action_page.php">
  <div class="imgcontainer">
    <img src="img_avatar2.png" alt="Avatar" class="avatar">
  </div>

  <div class="container">
    <label><b>Username</b></label>
    <input type="text" placeholder="Enter Username" name="uname" required>

    <label><b>Password</b></label>
    <input type="password" placeholder="Enter Password" name="psw" required>
        
    <button type="submit">Login</button>
    <input type="checkbox" checked="checked"> Remember me
  </div>

  <div class="container" style="background-color:#f1f1f1">
    <button type="button" class="cancelbtn">Cancel</button>
    <span class="psw">Forgot <a href="#">password?</a></span>
  </div>
</form>

<a href="articulo2.php">Otro artículo</a><br>
<a href="articulo3.php">Otro artículo</a><br>
<a href="articulo4.php">Otro artículo</a><br>
</div>

Puede tener cualquier cantidad de texto, pero se recomienda que sea breve, que no sea necesario desplazarse por ella, que el contenido principal pueda verlo el lector al primer vistazo.<br>
En la parte inferior del título están los botones para compartirla en las principales redes sociales.<br>
En el extremo inferior deben ir los botones que permitan a los lectores seguirnos en estos sitios sociales.<br>
<br>

<?php    
    include "include/share.php";   
?> 
