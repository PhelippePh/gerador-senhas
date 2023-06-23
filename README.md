# Projeto A3 
Cadastro e Banco de dados.

Sistema com:
<br>
<ul>
  <li>Tela de Home</li>
  <li>Tela de Login</li>
  <li>Cadastro</li>
  <li>Sessões</li>
  <li>Listagem de Registros</li>
  <li>Edição de Registros</li>
  <li>Deleção de Registros</li>
  <li>Pesquisa</li>
</ul>
<br>

Integraçao com banco de dados MySql
Utilizei O sistema PHP para fazer o backend do sistema, nele consiste em uma conexao
que se chama config.php nela eu consigo fazer a conexao manual entre o site e o MySql
utilizo Host para conectar.

Para o projeto funcionar basicamente o user coloca suas informaçoes em um formulario
eu faço a chamada desses dados, por meio do config.php eu envio os dados para o banco 
de dados, no Mysql salva os dados do user.
Na outra parte o user faz o Login no site com o Email e a senha cadastrada, eu faço uma
requisiçao e valido esses dados dentro do banco de dados, validaçao ocorrento corretamente 
o user consegue fazer o login no site, sendo negada ele nao entra.

  <li>Sistema</li>
  <br>

  Nesse projeto eu utilizo as requisiçoes de Get e Push para enviar e buscar as informaçoes 
  no banco de dados.

  Utilizo o barramento de eventos feito manualmente em PHP para fazer a comunicaçao entre 
  o software e o banco de dados Mysql.

  Variaveis sao feitas para armazenar corretamente as informaçoes passadas para o banco de dados.






