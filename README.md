# Controle de agendamentos e cadastros - Microsoft Power Plataform
<h2>⚔ Tecnologias Utilizadas</h2>

<div style="display: inline_block">

<b>Power Bi, Power Automate, Dataverse, Model Driven, Canvas App, JavaScript</b>
  
</div>

<h2>:bookmark_tabs: Descrição</h2>
<p><b>Esse projeto foi desenvolvido do zero com base no treinamento da Smart Consulting</b>
  
   - A empresa de petshop (Cuide Bem) estava precisando solucionar alguns problemas que estavam enfrentando no seu aplicativo e para isso decidimos utilizar a 
  power plataform para facilitar e baixar os custos do desenvolvimento. 
  - Este aplicativo possui a versão em <b>Canvas e Model Driven </b>
  - Foi utilizado o <b>Dataverse</b> para gerenciamento de banco de dados
  - <b>Power automate</b> para automatizar o envio de e-mail quando um agendamento for realizado
  - Power Bi para melhor análise de dados 
</p>

<h2>:bookmark_tabs: Configurações de segurança </h2>
<p>
   - O PetShop tem 3 unidades São Paulo(Principal), SP1 e SP2 <br>
   - Realizei a criação de duas unidades de negócio <b>Principal</b> e <b>Filiais</b><br>
   - Para unidade de são Paulo foi aplicado todos os direitos de acesso (tem acesso aos clientes e agendamentos das unidades SP1 e SP2 <br>
   - Para as filiais SP1 e SP2 foi aplicado apena o direito de acesso delas ou seja, elas não podem ver e nem editar usuários cadastrados em unidades diferentes.   
</p>


<h2>:bookmark_tabs: Entidade: Cliente</h2>
<p>
   - Foi nescessário criar scripts para a validação de CPF e criação de mascaras de formatação  <br>
   - Utilizei o power automate para o campo de pendências (Caso o cliente tenha pendência o valor será automaticamento acrescentado a próxima consulta) <br>
   - Criei uma View para os principais dados da entidades (Animais e Agendamentos) <br>
</p>
<h2>:bookmark_tabs: Entidade: Animal</h2>
<p>
   - Fiz uma referência do campo <b>Dono</b> para a entidade <b>Cliente</b> <br>
   - Criei um script para o campo Possui doença?, caso a resposta seja sim irá aparecer outro campo pedindo a descrição da doença.<br>
   - View dos principais dados da entidade <br>
</p>

<h2>:bookmark_tabs: Entidade: Agendamentos</h2>
<p>
   - Criei algumas referências para as entidades animal e cliente<br>
   - Criei um script para o campo <b>nome do animal</b> para vincular o animal ao <b>cliente</b>  <br>
   - Criei um script para o campo <b>Manso?</b>, Caso o animal não seja manso será acrescentado automaticamente 20% no valor do atendimento <br> 
   - Utilizei o Power Automate para automatizar o envio de e-mail, assim que o agendamento for realizado um e-mail é enviado ao cliente com as informações <br>
</p>

<h2>:bookmark_tabs: Model Driven</h2>
<p>
   - Criei Dashboards Somando o valor dos agendamentos com base no campo valor da entidade agendamentos<br>
   - Dashboards com o total de agendamentos por mês
</p>

<h2>:bookmark_tabs: CanvasApp</h2>
<p>
   - Desenvolvi um aplicativo canvas com todas as entidades e 100% funcional
</p>

<h2>:bookmark_tabs: Power Automate </h2>
<p>
   - Fiz os fluxos de automatização para envio de e-mail.
</p>

<h2>:bookmark_tabs: Power BI </h2>
<p>
   -  Fiz a integração com os entidades via Dataverse <br>
   -  Criei um painel com as seguintes vizualizações:<br>
             • Tipo de agendamentos por mês<br>
             • Agendamentos por Animal (Ranking)<br>
             • Valor Total por tipo de agendamento<br>
             • Valor por cliente
   
</p>



## Tela Inicial Canvas App
![Mobile 1](https://github.com/pe-salviano/Projeto_PetShop_PowerApps/blob/main/ImagensApp-PetShop/TelaInicial/TelaInicial-Petshop.png) 


## Tela Clientes
![Web 1](https://github.com/pe-salviano/Projeto_PetShop_PowerApps/blob/main/ImagensApp-PetShop/TelaClientes/TelaListaClientes%20-%20petshop.png)
![Web 2](https://github.com/pe-salviano/Projeto_PetShop_PowerApps/blob/main/ImagensApp-PetShop/TelaClientes/TelaDetalhesCliente%20-%20PetShop.png)
![Web 3](https://github.com/pe-salviano/Projeto_PetShop_PowerApps/blob/main/ImagensApp-PetShop/TelaClientes/TelaEditarCliente-%20Petshop.png)
![Web 4](https://github.com/pe-salviano/Projeto_PetShop_PowerApps/blob/main/ImagensApp-PetShop/TelaClientes/TelaCadastrarCliente%20-%20petshop.png)

## Tela Animal
![Web 1](https://github.com/pe-salviano/Projeto_PetShop_PowerApps/blob/main/ImagensApp-PetShop/TelaAnimais/TelaListaAnimais%20-%20petshop.png)
![Web 2](https://github.com/pe-salviano/Projeto_PetShop_PowerApps/blob/main/ImagensApp-PetShop/TelaAnimais/TelaDetalhesAnimais%20-%20petshop.png)
![Web 3](https://github.com/pe-salviano/Projeto_PetShop_PowerApps/blob/main/ImagensApp-PetShop/TelaAnimais/TelaEditarAnimais%20-%20petshop.png)
![Web 4](https://github.com/pe-salviano/Projeto_PetShop_PowerApps/blob/main/ImagensApp-PetShop/TelaAnimais/TelaCadastrarAnimais%20-%20petshop.png)


## Tela Agendamentos
![Web 1](https://github.com/pe-salviano/Projeto_PetShop_PowerApps/blob/main/ImagensApp-PetShop/TelaAgendamentos/TelaListaAgendamentos%20-petshop.png)
![Web 2](https://github.com/pe-salviano/Projeto_PetShop_PowerApps/blob/main/ImagensApp-PetShop/TelaAgendamentos/TelaDetalhesAgendamento%20-%20petshop.png)
![Web 3](https://github.com/pe-salviano/Projeto_PetShop_PowerApps/blob/main/ImagensApp-PetShop/TelaAgendamentos/TelaEditarAgendamento%20-%20petshop.png)
![Web 4](https://github.com/pe-salviano/Projeto_PetShop_PowerApps/blob/main/ImagensApp-PetShop/TelaAgendamentos/TelaAgendamentos%20-%20petshop.png)


## Aplicativo no Model Driven
![Mobile 1](https://github.com/pe-salviano/Projeto_PetShop_PowerApps/blob/main/ImagensApp-PetShop/App-ModelDriven/TelaContas%20-%20Model%20Drive.png) 
![Web 2](https://github.com/pe-salviano/Projeto_PetShop_PowerApps/blob/main/ImagensApp-PetShop/App-ModelDriven/TelaContasCliente%20%20-%20Model%20Drive.png)
![Web 3](https://github.com/pe-salviano/Projeto_PetShop_PowerApps/blob/main/ImagensApp-PetShop/App-ModelDriven/TelaAnimais%20-%20Model%20Drive.png)
![Web 4](https://github.com/pe-salviano/Projeto_PetShop_PowerApps/blob/main/ImagensApp-PetShop/App-ModelDriven/TelaCadastroAnimais%20%20-%20Model%20Drive.png)
![Web 5](https://github.com/pe-salviano/Projeto_PetShop_PowerApps/blob/main/ImagensApp-PetShop/App-ModelDriven/TelaAgendamentos%20%20-%20Model%20Drive.png)
![Web 6](https://github.com/pe-salviano/Projeto_PetShop_PowerApps/blob/main/ImagensApp-PetShop/App-ModelDriven/TelaAgendamentosAnimais-%20-%20Model%20Drive.png)


<div style="display: inline_block">
  
<a href = "mailto:pedro.salviano.cs@gmail.com"><img src="https://img.shields.io/badge/-Gmail-%23333?style=for-the-badge&logo=gmail&logoColor=white" target="_blank"></a>
<a href="https://www.linkedin.com/in/pedro-salviano-857917116/" target="_blank"><img src="https://img.shields.io/badge/-LinkedIn-%230077B5?style=for-the-badge&logo=linkedin&logoColor=white" target="_blank"></a>
<a href="https://pe-salviano.github.io/portfolio_pedro/" target="_blank"><img src="https://img.shields.io/badge/-Portf%C3%B3lio-brown?style=for-the-badge&logo=true" target="_blank"></a>
  
</div>



# Autor

Pedro Salviano da C. Silva

https://www.linkedin.com/in/pedro-salviano-desenvolvedor/

