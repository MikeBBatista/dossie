<html>
<body>
 <h1 align="center"> API 5º Semestre - 01/2022</h1>
 <h2> Parceiro Acadêmico: <a href="https://www.spcbrasil.org.br">SPC Brasil</a></h2>
  <h2 style="font-family:roboto;"> Resumo do Projeto :clipboard:</h2>
  <p align="justify" style="font-family:roboto;"> :chart_with_upwards_trend: O projeto é uma parceria entre a <a href="https://www.spcbrasil.org.br">SPC Brasil</a> e a FATEC São José dos Campos com a finalidade de desenvolvimento de um sistema capaz de centralizar os dados através de um Data Warehouse utilizando do mesmo para geração de análises e reports indicando para empresa a melhor abordagem e concentração de recursos afim de prospectar novos clientes e aumentar o consumo de seus produtos.</p>
  <p align="justify" style="font-family:roboto;">Nessa documentação será abordado o projeto da visão do desenvolvedor front-end, para mais informações gerais sobre o projeto <a href="https://github.com/API5Sem22/API5Doc">clique aqui</a></p>
  ---
  
  <h2 style="font-family:roboto;"> Tecnologias Adotadas :computer:</h2>
  
  * [Java](https://www.java.com/pt_BR/): Linguagem base para lógica do back-end;
  * [Spring Boot](https://spring.io/): Framework de Java para facilitação do desenvolvimento do back-end;
  * [Typescript](https://www.javascript.com/): Linguagem base para desenvolvimento do front-end;
  * [VueJS](https://vuejs.org): Framework que aceita a utilização do Typescript para facilitação do desenvolvimento do front-end, escolhido principalmente porque foi apresentado em sala de aula no semestre em questão;
  * [Microsoft SQL Server](https://www.microsoft.com/pt-br/sql-server/sql-server-downloads): Ferramenta utilizada para atender as demandas referentes ao banco de dados relacional da aplicação;
  * [CircleCI](https://circleci.com): Plataforma utilizada para implementação de práticas DevOps. Foi utilizada no projeto para supervisionar a qualidade do desenvolvimento;
  * [Power BI](https://powerbi.microsoft.com/pt-br/): Serviço de análise de dados. Utilizado na aplicação para demonstração de dados em formato de gráficos;
  * [Microsoft Azure](https://azure.microsoft.com/pt-br/services/sql-database/campaign/#overview): É uma plataforma destinada à execução de aplicativos e serviços, baseada nos conceitos da computação em nuvem. Foi utilizado para deploy do banco de dados SQL Server;
  * [SQL Server Integration Service](https://learn.microsoft.com/pt-br/sql/integration-services/sql-server-integration-services?view=sql-server-ver15): Serviço utilizado na aplicação para construção do ETL (Extract, Transform, Load) do banco de dados relacional para o Data Warehouse;
  * [Figma](https://www.figma.com/): Ferramenta utilizada para criação das telas pensando na melhor usabilidade da aplicação;
  * [Jira](https://vempracasa.atlassian.net/): Plataforma utilizada para cadastro e monitoramento das atividades realizadas pelo time;
  * [Heroku](https://www.heroku.com/platform): É uma plataforma em nuvem com um serviço que suporta várias linguagens de programação, nela foi realizado o deploy do Front-End da aplicação.
  ---
  
  <h2 style="font-family:roboto;"> Contribuições Individuais :dart:</h2>
<p align="justify" style="font-family:roboto;">Diferente dos projetos anteriores, o projeto em conjunto com a SPC Brasil não é apenas um projeto web, ele também é composto por uma análise de dados utilizando o PowerBI. Por isso, antes de iniciar o desenvolvimento referente ao front-end, foi necessário pensar na melhor de demonstrar os dados.</p>
 <p align="justify" style="font-family:roboto;">Utilizando do conhecimento dos projetos e experiências prévias, foi constatado que em conjunto com o VueJS seria aplicada a utilização de uma biblioteca de UI (User Interface) Syncfusion. Essa biblioteca consiste em uma enorme variedade de componentes pré construidos para utilização no VueJS. Para nossa aplicação, utilizamos principalmente, mas não unicamente, dos gráficos contidos no Syncfusion, que facilitaram a demonstração dos dados para o usuário em nossa aplicação.</p>
 <p align="justify" style="font-family:roboto;">Diferente do Angular que foi utilizado no projeto anterior, o VueJS não tem uma estrutura sólida e rígida, permitindo uma facilitação na fuga das boas práticas. Por isso nesse projeto, utilizei da mesma estrutura de projeto encontrada como padrão no Angular, sempre separando em componentes reaproveitaveis. Um conceito novo que apliquei nesse projeto foi o lazy loading, técnica que consiste em importar apenas os objetos solicitados, impedindo qualquer outro de carregar até que seja requisitado.</p>
   <details>
  <summary>Interface da aplicação</summary>
   <p align="center">
     <video src="https://user-images.githubusercontent.com/61523979/191330258-23a1ef9d-3dce-4f9e-bc2d-ffdb15ee8fda.mp4" controls="controls" style="max-rate: 730px;">
     </video>  
   </p>
  </details>
 <p align="justify" style="font-family:roboto;">A maior dificuldade do projeto foi assimilar o conhecimento de VueJS de forma que não houvesse débitos técnicos para o futuro da aplicação. Fui capaz de compreender conceitos novos, que se aplicam não só a Vue, como é o caso do lazy loading.</p>
 
  ---
   
  <h2 style="font-family:roboto;"> Aprendizados Efetivos :book:</h2>
 
 <h3 align="justify">Soft Skills</h3>
  <ul>
    <li>Agile Scrum:
      <ul>
        <li>Primeiro contato com Scrum;</li>
        <li>Quebra de Tasks;</li>
        <li>Organização e acompanhamento regular do desenvolvimento;</li>   
        <li>Equipe trabalhando como Squad;</li>
      </ul>
     </li>
   </ul>
 <br>
  <h3 align="justify">Hard Skills</h3>
  <ul>
     <li>VueJS (Aprendi a fazer com autonomia):
  <ul>
    <li>Estrutura de projeto;</li>
    <li>Reutilização de componentes;</li>   
    <li>Compreensão e utilização de Lifecycle Hooks</li>
    </ul></li>
   <br>
   <li>Integração front-back utilizando o VueJS (Aprendi a fazer com autonomia):
  <ul>
    <li>Configuração de chamadas das API's;</li>
    <li>Implementação e consumo dos serviços da API;</li>   
    <li>Envio de resposta para o back-end;</li>
    </ul></li>
   <br>
  </ul>
  </ul>
  <h2 align="center"> Navegação :books:</h2>
 <p align="justify" style="font-family:roboto;"><li><a href="https://github.com/MikeBBatista/dossie/blob/main/API_1.md">Projeto Apollo - O assistente virtual por comando de voz</a></li></p>
  <p align="justify" style="font-family:roboto;"><li><a href="https://github.com/MikeBBatista/dossie/blob/main/API_2.md">Projeto POC - A simplificação para lidar com formulários</a></li></p>
  <p align="justify" style="font-family:roboto;"><li><a href="https://github.com/MikeBBatista/dossie/blob/main/API_3.md">Projeto AirPLAN - O software que simplifica o tratamento dos documentos de aeronave</a></li></p>
 <p align="justify" style="font-family:roboto;"><li><a href="https://github.com/MikeBBatista/dossie/blob/main/API_4.md">Projeto #VEMPRACASA - Uma plataforma de gerenciamento de eventos</a></li></p>
  <p align="justify" style="font-family:roboto;"><li><a href="https://github.com/MikeBBatista/dossie/blob/main/README.md">Voltar para página inicial</a></li></p>
  
</body>
</html>
