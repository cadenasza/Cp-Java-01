# Checkpoint 1 Java Advanced
 
Programação em Java, JPA e Annotations

<img width="48" height="48" src="https://img.icons8.com/color/48/java-coffee-cup-logo--v1.png" alt="java-coffee-cup-logo--v1"/>
 
## Integrantes:
 
- Leonardo Cadena de Souza - RM557528
- Jennifer Eduarda Vieira Daleffi - RM557137
- Davi Gonzaga Ferreira - RM554890
 
## Entrega
 
• Este checkpoint será desenvolvido em grupo de 3 a 5 integrantes (não precisa ser o grupo
do Challenge);
 
• A entrega deverá ser feita via Teams com envio do arquivo diretamente ao professor (chat
direto), não via chat da disciplina;
 
• Para a presença na aula remota durante o período da avaliação, basta permanecer
conectado até 10 minutos antes do término da aula. Caso tenha qualquer dúvida, favor
enviar mensagem no chat direto com o professor que, por sua vez, retornará a resposta
para a sua dúvida;
 
• Entregue o(s) projeto(s) em formato .zip (ou .rar ou .7z), somente um integrante por
grupo, sendo que neste arquivo deve estar contido:
 
o Um arquivo .zip (ou .rar ou .7z) do programa elaborado no IDE IntelliJ, Eclipse ou
NetBeans (contendo todo o projeto, com a pasta, subpastas e arquivos desenvolvidos
no IDE de sua preferência, dentre os citados);
 
A entrega de um Relatório explicando o funcionamento do programa desenvolvido, contendo no início do Relatório os nomes e RMs de todos(as) os(as) integrantes do grupo. O Relatório deve conter a explicação das partes do código e as imagens das simulações. Ou, pode-se entregar um link para o ReadMe do seu projeto caso queira disponibilizá-lo em seu Github, com acesso liberado para o professor.
 
# Desenvolva o seguinte projeto:
 
1. Desenvolver um programa em Java que possua as seguintes classes e anotações:
   
## Uma classe para representar um funcionário contendo:
 
- O nome, as horas trabalhadas e o valor pago por horas trabalhadas;
- Implementar métodos para:
- Calcular e retornar o salário final de um funcionário;
- Mostrar as informações do funcionário.
  
## Criar uma subclasse para representar um funcionário sênior:
 
- A diferença é que um funcionário sênior recebe um bônus a cada 15 horas trabalhadas;
- Deve-se sobrescrever os métodos calcularSalario e imprimirInformacao.
  
## Criar mais subclasses para representar outros perfis de funcionários (use a criatividade nesta etapa).
 
## Criar uma classe para representar uma tabela com funcionários que tenha um método capaz de receber como parâmetro um objeto e gerar o código SQL automaticamente, capaz de selecionar todos os registros de uma tabela, contendo:
 
- Uma anotação @Tabela que possua um parâmetro nome indicando o nome da tabela
na qual a classe será mapeada (nome=”TAB_FUNCIONARIO”).
 
- Criar as colunas da tabela com anotações, representando os dados dos funcionários
(deve-se ajustar também os nomes das colunas e os respectivos parâmetros que o
grupo decidir colocar para cada coluna);
 
- Via API Reflection gerar automaticamente o código SQL necessário.
- Utilize o Entity Manager, Persistence Unit e Persistence Context com Hibernate para a
conexão com o BD.
 
Portanto, além da conexão com o BD Oracle SQL Developer, o programa deve fornecer o retorno do “código SQL” que está sendo realizado em cada etapa do CRUD (Create, Read, Update e Delete), além do retorno do “mostrar as informações do funcionário”. Abaixo, segue
um exemplo de tabela relacionada com a parte de retorno do “código SQL” para representar oque está ocorrendo em cada etapa junto ao BD:

• Data de entrega final do trabalho: até 30/03/2025 (domingo) às 23:59. 
 
• Entregas atrasadas em até 2 dias terão desconto de 50% na nota final. Após este período (em mais 2 dias), as entregas serão consideradas como 25% da nota. Após esse prazo, a nota zero será atribuída à atividade. 
 
• Qualquer outro tipo de entrega que não a solicitada neste documento, será desconsiderada. 
 
• Caso seja identificado qualquer tipo de vírus no(s) arquivo(s) entregues, será atribuída nota zero à atividade.
 
