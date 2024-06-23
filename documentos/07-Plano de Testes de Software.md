# Plano de Testes de Software

<span style="color:red">Pré-requisitos: <a href="https://github.com/ICEI-PUC-Minas-PMV-ADS/pmv-ads-2024-1-e1-proj-web-t12-fretelog/blob/main/documentos/02-Especifica%C3%A7%C3%A3o%20do%20Projeto.md"> Especificação do Projeto</a></span>, <a href="https://github.com/ICEI-PUC-Minas-PMV-ADS/pmv-ads-2024-1-e1-proj-web-t12-fretelog/blob/main/documentos/04-Projeto%20de%20Interface.md"> Projeto de Interface</a>

Os requisitos para realização dos testes de software são:
<ul><li>Site publicado na internet;</li>
<li>Navegador da internet: Chrome, Firefox ou Edge.</li>
</ul>

Os testes funcionais a serem realizados na aplicação são descritos a seguir.

<table>
 <tr>
  <th>Caso de teste</th>
  <th>Requisitos associados</th>
  <th>Objetivo do teste</th>
  <th>Passos</th>
  <th>Critérios de êxito</th>
  <th>Responsável</th>
 </tr>
 <tr>
  <td>CT-01: Verificar o funcionamento da pagina de cadastro.</td>
  <td>
   <ul>
    <li>RF-001:	O site deve permitir ao usuário cadastrar uma conta.</li>
   </ul>
  </td>
  <td>Verificar validações de campos, de confirmação de senha, e de conclusão do cadastro. </td>
  <td>
   <ol>
    <li>Acessar o navegador.</li>
    <li>Informar o endereço do site.</li>
    <li>Visualizar a página Home.</li>
    <li>Clicar nos links da página Home.</li>
   </ol>
   </td>
  <td>Todos os links da página Home devem encaminhar os usuários para as páginas descritas.</td>
  <td>Marlon</td>
 </tr>
</table>

<table>
 <tr>
  <th>Caso de teste</th>
  <th>Requisitos associados</th>
  <th>Objetivo do teste</th>
  <th>Passos</th>
  <th>Critérios de êxito</th>
  <th>Responsável</th>
 </tr>
 <tr>
  <td>CT-02: Verificar o funcionamento da pagina inicial.</td>
  <td>
   <ul>
    <li>RF-001:	O site deve permitir ao usuário cadastrar uma conta.</li>
    <li>RF-002:	A aplicação deve permitir ao usuário fazer o login da sua conta.</li> 
    <li>RF-013:	A aplicação deve ter um chat com suporte.</li> 
   </ul>
  </td>
  <td>Verificar se a pagina está direcionando para o cadastro, login e acesso ao chat de auto ajudo. </td>
  <td>
   <ol>
    <li>Acessar o navegador.</li>
    <li>Informar o endereço do site.</li>
    <li>Visualizar a pagina inicial.</li>
    <li>Clicar nos links da página inicial.</li>
   </ol>
   </td>
  <td>Todos os links da página Home devem encaminhar os usuários para as páginas descritas.</td>
  <td>Marlon</td>
 </tr>
</table>

<table>
 <tr>
  <th>Caso de teste</th>
  <th>Requisitos associados</th>
  <th>Objetivo do teste</th>
  <th>Passos</th>
  <th>Critérios de êxito</th>
  <th>Responsável</th>
 </tr>
 <tr>
  <td>CT-03: Verificar o funcionamento da pagina de login.</td>
  <td>
   <ul>
    <li>RF-001:	O site deve permitir ao usuário cadastrar uma conta.</li>
   <li>RF-003:	A aplicação deve permitir ao usuário atualizar e recuperar sua senha.</li>
   </ul>
  </td>
  <td>Verificar se a pagina está realizando o login e se está direcionando para a pagina de recuperar senha. </td>
  <td>
   <ol>
    <li>Acessar o navegador.</li>
    <li>Informar o endereço do site.</li>
    <li>Visualizar a pagina de login.</li>
    <li>Clicar nos links da pagina de login.</li>
   </ol>
   </td>
  <td>Todos os links da página Home devem encaminhar os usuários para as páginas descritas.</td>
  <td>Marlon</td>
 </tr>
</table>

<table>
 <tr>
  <th>Caso de teste</th>
  <th>Requisitos associados</th>
  <th>Objetivo do teste</th>
  <th>Passos</th>
  <th>Critérios de êxito</th>
  <th>Responsável</th>
 </tr>
 <tr>
  <td>CT-04: Verificar o funcionamento de recuperar a senha.</td>
  <td>
   <ul>
   <li>RF-003:	A aplicação deve permitir ao usuário atualizar e recuperar sua senha.</li>
   </ul>
  </td>
  <td>Verificar se a pagina está realizando a mensagem de recuperação de senha e se informar quando o e-mail não é cadastrado. </td>
  <td>
   <ol>
    <li>Acessar o navegador.</li>
    <li>Informar o endereço do site.</li>
    <li>Visualizar a pagina de recuperação de senha.</li>
    <li>Clicar nos links da pagina de recuperação de senha.</li>
   </ol>
   </td>
  <td>Todos os links da página Home devem encaminhar os usuários para as páginas descritas.</td>
  <td>Marlon</td>
 </tr>
</table>

<table>
 <tr>
  <th>Caso de teste</th>
  <th>Requisitos associados</th>
  <th>Objetivo do teste</th>
  <th>Passos</th>
  <th>Critérios de êxito</th>
  <th>Responsável</th>
 </tr>
 <tr>
  <td>CT-05: Verificar o funcionamento da pagina home do motorista.</td>
  <td>
   <ul>
   <li>RF-014:	A aplicação deve possuir uma pagina para o motorista visualizar os fretes disponíveis.</li>
   <li>RF-015:	A aplicação deve permitir um motorista agendar um trabalho quando houver disponibilidade de frete.</li>
   <li>RF-016:	A aplicação deve possuir uma pagina para o motorista visualizar o histórico de fretes realizados.</li>
   </ul>
  </td>
  <td>Verificar se a pagina está mostrando os fretes ofertados, direcionando para pagina de editar perfil, direcionando para a pagina de historico de fretes e testar botão de saida. </td>
  <td>
   <ol>
    <li>Acessar o navegador.</li>
    <li>Informar o endereço do site.</li>
    <li>Visualizar a pagina home motorista</li>
    <li>Clicar nos links da pagina home motorista.</li>
   </ol>
   </td>
  <td>Todos os links da página Home devem encaminhar os usuários para as páginas descritas.</td>
  <td>Marlon</td>
 </tr>
</table>

<table>
 <tr>
  <th>Caso de teste</th>
  <th>Requisitos associados</th>
  <th>Objetivo do teste</th>
  <th>Passos</th>
  <th>Critérios de êxito</th>
  <th>Responsável</th>
 </tr>
 <tr>
  <td>CT-06: Verificar o funcionamento da pagina de histórico de viagens.</td>
  <td>
   <ul>
   <li>RF-16:	A aplicação deve possuir uma pagina para o motorista visualizar o histórico de fretes realizados.</li>
   </ul>
  </td>
  <td>Verificar se a pagina está mostrando os fretes realizados. </td>
  <td>
   <ol>
    <li>Acessar o navegador.</li>
    <li>Informar o endereço do site.</li>
    <li>Visualizar a pagina de fretes realizados/li>
    <li>Clicar nos links da pagina de fretes realizados.</li>
   </ol>
   </td>
  <td>Todos os links da página Home devem encaminhar os usuários para as páginas descritas.</td>
  <td>Marlon</td>
 </tr>
</table>

<table>
 <tr>
  <th>Caso de teste</th>
  <th>Requisitos associados</th>
  <th>Objetivo do teste</th>
  <th>Passos</th>
  <th>Critérios de êxito</th>
  <th>Responsável</th>
 </tr>
 <tr>
  <td>CT-07: Verificar o funcionamento da pagina de editar perfil.</td>
  <td>
   <ul>
   <li>RF-05:	A aplicação deve permitir atualizar dados e documentos do usuário.</li>
   </ul>
  </td>
  <td>Verificar se a pagina está salvando as alterações do cadastro. </td>
  <td>
   <ol>
    <li>Acessar o navegador.</li>
    <li>Informar o endereço do site.</li>
    <li>Visualizar a pagina de editar perfil/li>
    <li>Clicar nos links da pagina de editar perfil.</li>
   </ol>
   </td>
  <td>Todos os links da página Home devem encaminhar os usuários para as páginas descritas.</td>
  <td>Marlon</td>
 </tr>
</table>

<table>
 <tr>
  <th>Caso de teste</th>
  <th>Requisitos associados</th>
  <th>Objetivo do teste</th>
  <th>Passos</th>
  <th>Critérios de êxito</th>
  <th>Responsável</th>
 </tr>
 <tr>
  <td>CT-08: Verificar o funcionamento do chat de suporte.</td>
  <td>
   <ul>
   <li>RF-13: A aplicação dever possuir um chat de suporte.</li>
   </ul>
  </td>
  <td>Verificar se o chat esta funcionando adequadamente . </td>
  <td>
   <ol>
    <li>Acessar o navegador.</li>
    <li>Informar o endereço do site.</li>
    <li>Verificar se o chat de suporte abre.</li>
    <li>Clicar nas alternativas para que possa ver se eles estão respondendo adequadamente .</li>
   </ol>
   </td>
  <td>O chat de suporte tem que mostra a reposta certa para a pergunta selecionada.</td>
  <td>Kayky</td>
 </tr>
</table>
