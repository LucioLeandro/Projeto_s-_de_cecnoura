<h1>Projeto Só de Cenoura</h1>

O projeto só de cenoura inclui a criação de três plataformas, duas delas interligadas, para o sistema de um restaurante,<br>
onde treremos :
- um app que será rodado em tablets com o menu, para os clientes o <a href"#cenouraapp">CenouraApp</a>
- um app que sera usado pelos garçons para anotar os pedidos, O<a href="#garconapp">Garconapp</a>, este será inteligado com o terceiro app que é
- um sistema que receberá o pedido anotado pelo garçon e o exibirá em uma tela na cozinha, o <a href="#cozinaapp">CozinhaApp</a>



<h3 id="cenouraapp">CozinhaApp</h3>

um simples aplicativo com duas telas, mostrando o cardápio do restaurante.

<h3 id="garconapp">garconapp</h3>

Usaremos o Material Design, criado pelo Google. O aplicativo Garçonapp será usado apenas pela equipe do restaurante, em um dispositivo Android comprado pelo proprietário. Então, usaremos um design do Google, que se integra bem ao Android, parece com um app normal.<br>

O framework que utilizarei é o Materialize, que não é o oficial do Google, mas é super fácil de usar. Para utilizá-lo, basta fazer o download no site. <br>

No fim, querocriar um app simples, que lista todas a opções de bolos e bebidas do cardápio. A garçonete irá clicar sobre o botão de cada item e o app irá marcá-los. Quando o pedido for completado, ela irá finalizar o pedido pressionando um botão da parte inferior. Com isso, o pedido irá chegar diretamente na cozinha. Tudo será feito utilizando o design do Material Design, com componentes do Materialize.



<h3 id="cozinhaapp">CozinhaApp</h3>

É um projeto Meteor feito por terceiro que incorporei e recebe o pedido feito através do garconapp.
