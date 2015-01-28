# testeapk
aprendendo sobre Phonegap
<HTML>
<HEAD>
</HEAD>
<BODY>
<style>
body{margin:0; padding:0; border:none; background:#333;}
img{display:hidden;}

ul{
  float:left;
  display:block;
  width:260px;
  height:auto;
  margin:0;
  border:none;
}

li{
  float:left;
  text-decoration:none;
  display:table;

  width:200px;
  height:40px;
  background:#444;
  -webkit-transition: height 0.4s;
  
}

li:hover{
background:#ee1552;
color:#fff;
height:90px;
alignment-baseline:bottom;
  image-
}

p{
  font-family:Century Gothic, Arial, Helvetica;
  font-size:20px;
   display: table-cell;
   text-align: center;
   vertical-align: middle;
}
</style>

<ul>
  <li onClick="cadastraNome()"><p>Nome</p></li>
  <li onClick="idade()"><p>Idade</p></li>
  <li onClick="altura()"><p>Altura</p></li>
  <li onClick="peso()"><p>Peso</p></li>
  <li onClick="imc()"><p>Calcular</p></li>
  
</ul>

<tr>
  <td><p>Bem vindo <span id="nome"></p></span></td><br />
  <td><p>Idade: <span id="idade"></p></span></td><br />
  <td><p>Altura: <span id="altura"></p></span></td><br />
  <td><p>Peso: <span id="peso"></p></span></td><br />
  <td><p>  <span id="imc"></p></span></td><br />
</tr>
</BODY>
</HTML>
