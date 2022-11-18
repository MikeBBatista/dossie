<html>
<body>
 <h1 align="center"> API 6º Semestre - 02/2022</h1>
 <h2> Parceiro Acadêmico: <a href="https://www.domrock.net/">Dom Rock</a></h2>
  <h2 style="font-family:roboto;"> Resumo do Projeto :clipboard:</h2>
  <p align="justify" style="font-family:roboto;"> :chart_with_upwards_trend: O projeto é uma parceria entre a <a href="https://www.domrock.net/">Dom Rock</a> e a FATEC São José dos Campos com a finalidade de desenvolver uma ferramenta capaz de armazenar, processar e relatar dados de mais de uma fonte. A equipe D-end ofereceu uma solução que é capaz de realizar o tratamento e correlação entre os dados afim de evidenciar quaisquer inconsistências entre os pagamentos das faturas quanto convênios médicos, que no caso, são os dados em necessidade de tratamento par o cliente.</p>
  <p align="justify" style="font-family:roboto;">Nessa documentação será abordado o projeto da minha visão como desenvolvedor, para mais informações gerais sobre o projeto <a href="https://github.com/API6Sem22/API6Doc">clique aqui</a></p>
  ---
  
  <h2 style="font-family:roboto;"> Tecnologias Adotadas :computer:</h2>
  
  * [MongoDB](https://www.mongodb.com/): É um banco de dados NoSQL orientado a documentos, por ser schema free, pode ser utilizado de forma flexivel. Foi aplicado para armazenamento dos dados fornecidos pelo cliente, além do tratamento dos mesmos usando a ferramenta Aggregation Framework;
  * [Python](https://www.python.org/): É uma linguagem de programação muito flexivel e de fácil desenvolvimento por ser de alto nível, apesar de possuir grande complexidade dependendo da necessidade. Foi utilizada para codificação de scripts de ETL (Extract, Transform, Load) do sistema, realizando a carga dos dados para o MongoDB e SQL Server.;
  * [Microsoft SQL Server](https://www.microsoft.com/pt-br/sql-server/sql-server-downloads): Ferramenta utilizada para atender as demandas referentes ao banco de dados relacional da aplicação;
  * [Power BI](https://powerbi.microsoft.com/pt-br/): Serviço de análise de dados. Utilizado na aplicação para demonstração de dados em formato de gráficos;
  * [Microsoft Azure](https://azure.microsoft.com/pt-br/services/sql-database/campaign/#overview): É uma plataforma destinada à execução de aplicativos e serviços, baseada nos conceitos da computação em nuvem. Foi utilizado para deploy do banco de dados SQL Server;
  * [Jira](https://vempracasa.atlassian.net/): Plataforma utilizada para cadastro e monitoramento das atividades realizadas pelo time;
  * [Heroku](https://www.heroku.com/platform): É uma plataforma em nuvem com um serviço que suporta várias linguagens de programação, nela foi realizado o deploy do Front-End da aplicação.
  ---
  
  <h2 style="font-family:roboto;"> Contribuições Individuais :dart:</h2>
<p align="justify" style="font-family:roboto;">O último projeto do curso foi uma surpresa um tanto quanto inesperada. Diferente dos projetos passados, o projeto em parceria com a Dom Rock, não possui a necessidade de uma aplicação com desenvolvimento voltado para o front-end, minha até então maior expertise. Apesar de ter ficado inseguro a primeiro momento, logo no início do projeto provei que meus conhecimentos vão além do front-end.</p>
 <p align="justify" style="font-family:roboto;">As tarefas que realizei foram todas voltadas para o tratamento dos dados enviados como documentos para o MongoDB, por isso, a primeira instância me registrei em um curso voltado para a tecnologia do Mongo (M001 MongoDB Basics). Finalizado o curso, pude realizar as tarefas de todas as sprints sem maiores entraves.</p>
 <p align="justify" style="font-family:roboto;">Para realização dos tratamento, utilizei scripts conhecidos como aggregations que possibilitam uma série de filtros e comandos para que o dado seja modificado e polido. Durante o projeto, novas informações surgiam a cada sprint, fazendo com que esses scripts sofressem alterações constantes. Um exemplo que vale a pena citar foi a informação de que uma das necessidades do cliente era salvar os dados descartados pelo tratamento. Apesar das modificações, com um pouco mais de pesquisa, todas as aggregations foram realizadas com êxito, com direito a elogio do cliente.</p>
 <p align="justify" style="font-family:roboto;">Apesar de ter confiança nas minha habilidades, esse projeto reafirmou que estou pronto para trabalhar como um profissional completo na área de tecnologia, pois apesar de estar acostumado a trabalhar voltado para o front-end, meu conhecimento técnico me permite saber estudar novos tópicos, possibilitando minha capacitação para atuar em qualquer modalidade na hora de desenvolver.</p>
 
  ---
   
  <h2 style="font-family:roboto;"> Aprendizados Efetivos :book:</h2>
 
 <h3 align="justify">Soft Skills</h3>
 
 * <b>Comunicação:</b> Durante o desenvolvimento, com o tratamento dos dados, a comunicação foi crucial para alinhar com a equipe e com o cliente o que era esperado dos dados ao final dos ajustes.;
 * <b>Flexibilidade E Resiliência:</b> Como nesse projeto fui pego de surpresa por sua falta de front-end, precisei superar um sentimento inicial de desânimo.;
 * <b>Proatividade:</b> Começar um curso antes do início oficial da primeira sprint, afim de ser útil para o time e realizar minhas tarefas sem requisitar ajuda, foi o maior motivador para minha proatividade.
 <br>
  <h3 align="justify">Hard Skills</h3>
  <ul>
     <li>MongoDB (Aprendi a fazer com autonomia):
  <ul>
    <li>Estrutura dos dados;</li>
    <li>Aggregations;</li>   
    <li>Consultas e alterações dos dados</li>
    </ul></li>
   <br>
   <li>Agile Scrum (Aprendi a fazer com autonomia):
    <ul>
      <li>Aprendizagem contínua;</li>
      <li>Aplicação mais acertiva;</li>
     </ul></li>
  </ul>
  </ul>
  <h2 align="center"> Navegação :books:</h2>
 <p align="justify" style="font-family:roboto;"><li><a href="https://github.com/MikeBBatista/dossie/blob/main/API_1.md">Projeto Apollo - O assistente virtual por comando de voz</a></li></p>
  <p align="justify" style="font-family:roboto;"><li><a href="https://github.com/MikeBBatista/dossie/blob/main/API_2.md">Projeto POC - A simplificação para lidar com formulários</a></li></p>
  <p align="justify" style="font-family:roboto;"><li><a href="https://github.com/MikeBBatista/dossie/blob/main/API_3.md">Projeto AirPLAN - O software que simplifica o tratamento dos documentos de aeronave</a></li></p>
 <p align="justify" style="font-family:roboto;"><li><a href="https://github.com/MikeBBatista/dossie/blob/main/API_4.md">Projeto #VEMPRACASA - Uma plataforma de gerenciamento de eventos</a></li></p>
 <p align="justify" style="font-family:roboto;"><li><a href="https://github.com/MikeBBatista/dossie/blob/main/API_5.md">Projeto Data Rangers - Ferramenta de análise de dados para prospecção de novos clientes</a></li></p>
  <p align="justify" style="font-family:roboto;"><li><a href="https://github.com/MikeBBatista/dossie/blob/main/README.md">Voltar para página inicial</a></li></p>
  
</body>
</html>
