
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

En esta herramienta podras accesar al sistema de archivos en la nube de grupo ack. por favor inicia con tu nombre de usuario y contraseña. <br>
<img style="margin:12px 0 12px 0;" src="img/acklogo.png" width="620" height="400" alt="Imagen para el intro" title="Mi sitio web, actualidad y tecnologia"><br>


<style>
form {

}
input[type=text], input[type=password] {
    width: 80%;
    padding: 12px 10px;
    margin: 0px 0;
    display: block;
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
    width: 40%;
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
    width: 50%;
    border-radius: 50%;
}
.container {
    padding: 10px;
}
span.psw {
    float: right;
    padding-top: 16px;
}
/* Change styles for span and cancel button on extra small screens */
@media screen and (width: 100px) {
    span.psw {
       display: block;
       float: none;
    }
    .cancelbtn {
       width: 50%;
    }
}
</style>

<h2>Formato de ingreso</h2>

<form action="/action_page.php">
  <div class="imgcontainer">
    <img src="acklogo.png" alt="Avatar" class="avatar">
  </div>

  <div class="container">
    <label><b>Username</b></label>
    <input type="text" placeholder="Enter Username" name="uname" required>

    <label><b>  Password</b></label>
    <input type="password" placeholder="Enter Password" name="psw" required>
        
    <button type="submit">Login</button>
    <input type="checkbox" checked="checked"> Remember me
  </div>

  
</form>

</div>
