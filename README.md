# Checkpoint 1 Java Advanced
 
Programação em Java, JPA e Annotations

<svg xmlns="http://www.w3.org/2000/svg" x="0px" y="0px" width="48" height="48" viewBox="0 0 48 48">
<path fill="#F44336" d="M23.65,24.898c-0.998-1.609-1.722-2.943-2.725-5.455C19.229,15.2,31.24,11.366,26.37,3.999c2.111,5.089-7.577,8.235-8.477,12.473C17.07,20.37,23.645,24.898,23.65,24.898z"></path><path fill="#F44336" d="M23.878,17.27c-0.192,2.516,2.229,3.857,2.299,5.695c0.056,1.496-1.447,2.743-1.447,2.743s2.728-0.536,3.579-2.818c0.945-2.534-1.834-4.269-1.548-6.298c0.267-1.938,6.031-5.543,6.031-5.543S24.311,11.611,23.878,17.27z"></path><g><path fill="#1565C0" d="M32.084 25.055c1.754-.394 3.233.723 3.233 2.01 0 2.901-4.021 5.643-4.021 5.643s6.225-.742 6.225-5.505C37.521 24.053 34.464 23.266 32.084 25.055zM29.129 27.395c0 0 1.941-1.383 2.458-1.902-4.763 1.011-15.638 1.147-15.638.269 0-.809 3.507-1.638 3.507-1.638s-7.773-.112-7.773 2.181C11.683 28.695 21.858 28.866 29.129 27.395z"></path><path fill="#1565C0" d="M27.935,29.571c-4.509,1.499-12.814,1.02-10.354-0.993c-1.198,0-2.974,0.963-2.974,1.889c0,1.857,8.982,3.291,15.63,0.572L27.935,29.571z"></path><path fill="#1565C0" d="M18.686,32.739c-1.636,0-2.695,1.054-2.695,1.822c0,2.391,9.76,2.632,13.627,0.205l-2.458-1.632C24.271,34.404,17.014,34.579,18.686,32.739z"></path><path fill="#1565C0" d="M36.281,36.632c0-0.936-1.055-1.377-1.433-1.588c2.228,5.373-22.317,4.956-22.317,1.784c0-0.721,1.807-1.427,3.477-1.093l-1.42-0.839C11.26,34.374,9,35.837,9,37.017C9,42.52,36.281,42.255,36.281,36.632z"></path><path fill="#1565C0" d="M39,38.604c-4.146,4.095-14.659,5.587-25.231,3.057C24.341,46.164,38.95,43.628,39,38.604z"></path></g>
</svg>
 
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
 
