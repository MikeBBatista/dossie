 <h1 align="center"> API 2º Semestre</h1>
  
  <h2 style="font-family:roboto;"> Resumo do Projeto :clipboard:</h2>
  
<p align="justify" style="font-family:roboto;"><b>POC (Processos Otimizados de Contas)</b> é uma aplicação desktop criada para facilitar a inserção ou modificação de dados referentes a contas de luz e água de uma empresa, afim de gerar um relatório detalhado de seus consumos. A aplicação visa auxiliar o usuário a cadastrar as informações mais pertinentes encontradas em cada conta, e também em auxiliar na geração de relatórios sobre a contribuição de cada usuário para inserção ou modificação dos dados.</p>
    <p align="justify" style="font-family:roboto;"> As funcionalidades da POC incluem: 
  <ul>
    <li>Cadastrar fornecedores.</li>
    <li>Cadastrar clientes.</li>
    <li>Cadastrar contas.</li>
    <li>Editar informações cadastradas.</li>
    <li>Gerar relatório de consumo.</li>
    <li>Gerar relatório de colaborador.</li>
  </ul>
 </p>
  <p align="justify" style="font-family:roboto;">Nessa documentação será abordada a visão de um único desenvolvedor do projeto, para mais informações gerais <a href="https://gitlab.com/apolo-pi-fatec/apolo">clique aqui</a></p>
  ---
  
  <h2 style="font-family:roboto;"> Tecnologias Adotadas :computer:</h2>
   
  * [Java](https://www.java.com/pt_BR/)
  * [MySQL](https://dev.mysql.com/doc/)
  
  ---
  
  <h2 style="font-family:roboto;"> Contribuições Individuais :dart:</h2>
  <h4 style="font-family:roboto;">AS ATRIBUIÇÕES DO SCRUM MASTER</h4>
  <p align="justify" style="font-family:roboto;">As atribuições do scrum master estão presentes em todas as etapas da criação do projeto. Junto ao product owner o scrum master precisa avaliar o que sua equipe consegue entregar e priorizar as tasks de maior importância. Assim como também auxiliar os desenvolvedores com seu conhecimento técnico afim de impedir congestionamento durante as sprints de desenvolvimento.</p>
  <h4 style="font-family:roboto;">A ESCOLHA DA TECNOLOGIA</h4>
  <p align="justify" style="font-family:roboto;">Como projeto integrador do segundo semestre, a tecnologia atribuida pro projeto foi escolhida inteiramente pela instituição de ensino, que desejava que os alunos aplicassem seu conhecimento adquirido naquele semestre, voltados para o Java e MySQL. Apesar da restrição, a problemática apresentada para o projeto era simples e não necessitava de outras tecnologias que não as requeridas pela instituição.</p>
  <h4 style="font-family:roboto;">POR QUE JAVA?</h4>
   <p align="justify" style="font-family:roboto;">Apesar de existirem diversas tecnologias que poderiam ter sido utilizadas para a abordagem do projeto, dado o momento acadêmico dos alunos, a escolha é propícia para o aprendizado. O segundo semestre do curso de Banco de Dados na Fatec, visa desenvolver o conhecimento e os conceitos da linguagem de programação, diferente do primeiro semestre que visava o desenvolvimento da capacidade lógica do estudante. Dentro deste contexto, Java é uma linguagem robusta e de fácil entendimento para diversos conceitos de linguagem, como por exemplo construção de classes e criação e manipulação de objetos.</p>
  <p align="justify" style="font-family:roboto;">A arquitetura do projeto foi montada com o intuito de facilitar a manutenção, implementação ou mudanças no código, seguindo as boas práticas aconselhadas para programação em Java.</p>
  <details>
  <summary>Demonstração da Arquitetura do Projeto</summary>
  <br>
   <img style="border-radius: 50%;" src="https://user-images.githubusercontent.com/46934773/167305456-e41ef307-01ed-4a60-b94c-940d271fc478.png" alt=""/>
  </details>
  <p align="justify" style="font-family:roboto;">Cada pasta representa uma parte específica do projeto, contendo todos os arquivos daquela parte específica. A pasta entities, por exemplo, guarda as classes que existem no projeto, enquanto que a pasta dao guarda os arquivos com metodos direcionados para inserção ou modificação de dados referente a cada tipo de classe no banco. Essa configuração permite uma melhor visualização do código, e uma separação concreta por etapas, que possibilita mudanças acertivas de acordo com a necessidade, sem que afete outra parte que não tem uma ligação dependente daquilo que será mudado.</p>
    <p align="justify" style="font-family:roboto;">Outra diferenciação e facilidade pertinente ao Java é sua tenacidade quanto a criação de uma interface para um projeto, diferente de um projeto web, que utiliza de html e css para criar uma interface amigavél para o usuário, o Java também possui bibliotecas próprias voltadas para o desenvolvimento de interfaces, facilitando a criação de uma aplicação desktop. Abaixo um exemplo de código para interface e sua representação em GUI Builder (biblioteca própria do java para interfaces).</p>
      <details>
  <summary>Demonstração do Código de Interface Java</summary>
  <br>
   <img style="border-radius: 50%;" src="https://user-images.githubusercontent.com/46934773/167306812-6f8a1f01-7f27-4f71-9a64-f1a76d14a301.png" alt=""/>
  </details>
   <details>
  <summary>Demonstração de Interface em Java</summary>
  <br>
   <img style="border-radius: 50%;" src="https://user-images.githubusercontent.com/46934773/167306860-1588628b-7e15-4f1f-8040-0ffed8bf3bdb.png" alt=""/>
  </details>
    <h4 style="font-family:roboto;">Considerações finais</h4>
    <p align="justify" style="font-family:roboto;">O projeto do segundo semestre deixa claro as intenções da instituição de forçar o aluno a desafiar os conhecimentos passados pelos professores. Todo conteúdo dado em sala de aula foi aplicado ao projeto, mas para sua execução ainda foi necessário vontade, criatividade e curiosidade por parte dos estudantes, pois muitas vezes o conhecimento passado pelos professores era limitado propositalmente para instigar ao aluno autonomia em suas pesquisas, sempre podendo contar com o auxílio do corpo acadêmico da instituição para esclarecimento de eventuais dúvidas.</p>
  ---
   
  <h2 style="font-family:roboto;"> Aprendizados Efetivos :book:</h2>   
    <ul>
    <li>Agile Scrum:
    <ul>
      <li>Quebra de Tasks;</li>
      <li>Organização e acompanhamento regular do desenvolvimento;</li>   
      <li>Equipe trabalhando como Squad;</li>
     </ul></li>
    <li>Java:
    <ul>
      <li>Estrutura e arquitetura de código;</li>
      <li>Construção de classes;</li>   
      <li>Manipulação de objetos;</li>
      <li>Criação de tela através do GUI Builder;</li>
      </ul></li>
  </ul>
  
  ---