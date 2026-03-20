<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>

<title>Página de Cadastro</title>
</head>
<body>
    <header><h1>Formulário de Cadastro</h1></header>
    <hr>
    
</body>
<main>

<form action="index.html" method="get">

    <label for="text">Seu texto</label><br>
   
<input required type="text" id="name" name="nome">


<label for="email">Seu email</label><br>
<input type="email"><br>

    <label for="passoword">Sua senha</label><br>
<input type="password"><br>
   
    <label for="number">Seu número</label><br>
 <input type="number"><br>
    
    <label for="date">Sua data de nascimento</label><br>
<input type="date"><br>
<hr>

    <label for="radio">Masculino</label>
<input type="radio" name="genero"
value="Masculino"><br>

    <label for="radio">Feminino</label>
<input type="radio" name="genero"
value="Feminino"><br>

    <label for="radio">Prefiro não responder</label>
<input type="radio" name="genero"
value="Prefiro não responder"><br>
<hr>

<label for="estado">Seu estado:</label>
<select name="estado">
  <option value="sp">São Paulo</option>
  <option value="rj">Rio de Janeiro</option>
  <option value="ba">Bahia</option><br>
</select>
<hr>

<label for="checkbox">Quais linguagens de programação você conhece?</label><br>

<input type="checkbox" id="html" name="linguagens" value="html">
<label for="html"> HTML </label><br>

<input type="checkbox" name="linguagens" value="css">
<label for="css">CSS</label><br>

<input type="checkbox" name="linguagens" value="java">
<label for="java">JavaScript</label><br>

<fieldset>

<legend>Observações</legend>
<textarea id="msg"></textarea>

</fieldset>

</form>
<footer> 
    <h3>Usuário do GITHUB: joaoalbergaria350-afk</h3>
</footer>
</main>
</html>
