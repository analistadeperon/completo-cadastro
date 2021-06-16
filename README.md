# completo-cadastro

<div id="root"></div>


<!DOCTYPE html PUBLIC "-//W3C//DTD XHTML 1.0 Transitional//EN" "http://www.w3.org/TR/xhtml1/DTD/xhtml1-transitional.dtd">
<html xmlns="http://www.w3.org/1999/xhtml">
<head>
<meta http-equiv="Content-Type" content="text/html; charset=iso-8859-1" />
<title>Cadastro de Clientes</title>
<script language="JavaScript">
function excluir(url){
if (confirm("Confirma exclusão do registro?")){
document.location = url;
}
}
</script>
</head>

<body>
  <!DOCTYPE html PUBLIC "-//W3C//DTD XHTML 1.0 Transitional//EN" "http://www.w3.org/TR/xhtml1/DTD/xhtml1-transitional.dtd">
<html xmlns="http://www.w3.org/1999/xhtml">
<head>
<meta http-equiv="Content-Type" content="text/html; charset=iso-8859-1" />
<title>Cadastro de Clientes</title>
<script language="JavaScript">
function excluir(url){
if (confirm("Confirma exclusão do registro?")){
document.location = url;
}
}
</script>
</head>

<body>
<p><h1>Cadastro de Empresa</h1></p>

<form id="f1" name="f1" method="post" action="cadclientes.php">
<table bgcolor="#0000FF" width="40%" border="0" cellspacing="0" cellpadding="1">
<tr>
<td><table bgcolor="#CCCCCC" width="100%" border="0" cellspacing="1" cellpadding="1">
<tr>
<td>Nome: </td>
<td><input name="nome" type="text" id="nome" size="50" maxlength="50" /></td>
</tr>
<tr>
<td>CNPJ:</td>
<td><input name="cnpj" type="text" id="cnpj" size="50" maxlength="50" /></td>
</tr>

<td>Inscrição:</td>
<td><input name="inscrição" type="text" id="inscrição" size="50" maxlength="50" /></td>
<tr>
<td>Endere&ccedil;o:</td>
<td><input name="endereco" type="text" id="endereco" size="50" maxlength="50" /></td>
</tr>
<tr>
<td>Bairro:</td>
<td><input name="bairro" type="text" id="bairro" size="50" maxlength="50" /></td>
</tr>
<td>CEP: </td>
<td><input name="cep" type="text" id="cep" size="50" maxlength="50" /></td>
<tr>
<td colspan="2"><label>
<input type="submit" name="Submit" value="Cadastrar" />
</label>
<label>
<input type="button" name="Submit2" value="Limpar" />
</label></td>
</tr>
</table></td>
</tr>
</table>
</form>
<p><h1>Cadastro de Clientes</h1></p>

<form id="f1" name="f1" method="post" action="cadclientes.php">
<table bgcolor="#0000FF" width="40%" border="0" cellspacing="0" cellpadding="1">
<tr>
<td><table bgcolor="#CCCCCC" width="100%" border="0" cellspacing="1" cellpadding="1">
<tr>
<td>Nome: </td>
<td><input name="nome" type="text" id="nome" size="50" maxlength="50" /></td>
</tr>
<td>CPF: </td>
<td><input name="cpf" type="text" id="cpf" size="50" maxlength="50" /></td>
<tr>
<td>Cidade:</td>
<td><input name="cidade" type="text" id="cidade" size="50" maxlength="50" /></td>
</tr>
<tr>
<td>Endere&ccedil;o:</td>
<td><input name="endereco" type="text" id="endereco" size="50" maxlength="50" /></td>
</tr>
<td>CEP: </td>
<td><input name="cep" type="text" id="cep" size="50" maxlength="50" /></td>
<tr>
<td>Bairro:</td>
<td><input name="bairro" type="text" id="bairro" size="50" maxlength="50" /></td>
</tr>

<tr>
<td colspan="2"><label>
<input type="submit" name="Submit" value="Cadastrar" />
</label>
<label>
<input type="button" name="Submit2" value="Limpar" />
</label></td>
</tr>
</table></td>
</tr>
</table>
</form>
<html><head><title> Formulário Padrão HTML SEMJavaScript </title></head><body><FORM ACTION="mailto:teste@gmail.com" METHOD="POST" ENCTYPE="text/plain" NAME="cadastro"><p>Por favor, preencha os campos abaixo e depois clique no botão Enviar. Caso necessite apagar os dados, dê um clique no botão Limpar.<br> Muito Obrigado! <br><br><br></p>Nome Completo:   <INPUT TYPE="TEXT" NAME="nome" SIZE="35"> Seu e-mail: <INPUT TYPE="TEXT" NAME="email" SIZE="35"> <br>Sexo:<br><INPUT TYPE="RADIO" NAME="sexo" VALUE="f"> Feminino <br><INPUT TYPE="RADIO" NAME="sexo" VALUE="m"> Masculino <br><br>Estado Civil:<br><INPUT TYPE="RADIO" NAME="civil" VALUE="s"> Solteiro <br><INPUT TYPE="RADIO" NAME="civil" VALUE="c"> Casado <br><INPUT TYPE="RADIO" NAME="civil" VALUE="e"> Enrolado <br><br>Bens que possui:<br><INPUT TYPE="CHECKBOX" NAME="bens" VALUE="c"> Casa <br><INPUT TYPE="CHECKBOX" NAME="bens" VALUE="a"> Automovel <br><INPUT TYPE="CHECKBOX" NAME="bens" VALUE="m"> Moto <br><br>Faixa de idade:  <SELECT NAME="faixaidade"><OPTION VALUE="3a10"> 3 a 10 anos<OPTION VALUE="11a25"> 11 a 25 anos<OPTION VALUE="26a35"> 26 a 35 anos<OPTION VALUE="36a55"> 36 a 55 anos<OPTION VALUE="56a90"> 56 a 90 anos</SELECT>Hobby preferido: <SELECT NAME="hobby"><OPTION VALUE="livros"> Ler livros<OPTION VALUE="musica"> Ouvir música<OPTION VALUE="cinema"> Assistir filmes<OPTION VALUE="esporte"> Praticar esportes<OPTION VALUE="games"> Jogar games</SELECT><br><br>Observações Gerais:<br><TEXTAREA NAME="observacoes" ROWS="5" COLS="60"></TEXTAREA><br><INPUT TYPE="SUBMIT" VALUE="Enviar os dados"><INPUT TYPE="RESET" VALUE="Limpar os dados"></FORM></body></html>
