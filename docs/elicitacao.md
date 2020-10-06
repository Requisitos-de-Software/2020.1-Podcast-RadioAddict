

**Elicitação de Requisitos**

**Introspecção** 
================

Introspecção é uma técnica muito rica e profunda. Consiste em entender
quais propriedades o sistema deve possuir para que seja um sucesso.
Demanda o Engenheiro de Requisitos imaginar o que ele gostaria, se ele
tivesse que desempenhar uma dada tarefa, com os equipamentos disponíveis
e demais recursos.

**Personas:**
-------------

Persona é um personagem fictício de um grupo de usuários reais, criada
para descrever um usuário típico. As personas são definidas por seus
objetivos, que são determinados num processo de refinamentos sucessivos
durante a investigação inicial do domínio de atividade do usuário

**Persona 1**
-------------

** **

 Persona  |  Aspirante Matias 
  :--------- | :------ 
  Nome                                        | André Mathias
  Profissão                                   | Policia
  Escolaridade                                | Superior Incompleto
  Nível de conhecimentos sobre o aplicativo   | Começou a utilizar o aplicativo recentemente para a pesquisa de carros roubados e acessar a lista de procurados.
  História de contexto                        | Matias vive em uma cidade muito violenta. Virou policial por incentivo do seu pai que também era policial. Trabalha em período plantão em um ambiente bem estressante. Para facilitar a sua vida, passou a utilizar o aplicativo, pois, na maioria das vezes, é um forma mais rápida de pesquisa do que utilizar as ferramentas disponibilizadas pela corporação.
  Sugestão para melhoria                     | Melhorar a infraestrutura do aplicativo, as vezes não consigo fazer as pesquisa com rapidez. Também poderiam

### **Requisitos Elicitados (Introspecção - Persona 1)** 

** **

 Código  | Descrição |  Prioridade
  :--------- | :------: | :------
  RF01    | possibilidade de buscar pendências judiciais   | Must
  RF02    | Visualizar a lista de procurados pela justiça  | Must
  RF03    | Realizar pesquisas sucessivas                  | Must

**Persona 2**
-------------

** **

Persona  |  Guilherme de Oliveira
  :--------- | :------ 
  Nome                                       | Guilherme de Oliveira
  Profissão                                  | Administrador de Empresas
  Escolaridade                               | Superior Completo
  Nível de conhecimentos sobre o aplicativo  | Não conhecia o aplicativo Sinesp até ser sugerido o seu uso.
  História de contexto                       | Guilherme trabalha no Banco Central como gerente de negócios. Ele sempre chega ao trabalho pontualmente e sempre vai embora ao anoitecer. Na última vez que ele foi para o trabalho, ao sair do seu carro no estacionamento, foi abordado por duas pessoas e levaram o seu carro. Guilherme conversando com o seu colega de trabalho, foi sugerido que ele fizesse uma ocorrência e que, também, baixasse o aplicativo Sinesp para registrar o roubo de seu carro.
  Sugestão para melhoria                      | Melhorar o sistema de cadastrar um roubo de carro. Para fazê-lo atualmente, precisei criar uma conta .gov e demorei ter acesso a minha conta para que, assim, eu concluísse o cadastro do roubo do meu carro

### **Requisitos Elicitados (Introspecção - 2)** 

** **

  
 Código  | Descrição |  Prioridade
  :--------- | :------: | :------
  RF01    | Realizar busca de situação do carro  | Must       
  RF02    | Realizar cadastro de carro roubado/furtado  |  Must
             

**Persona 3**
-------------

** **

Persona  |   Maria Aparecida
  :--------- | :------ 
  Nome                                       | Maria Aparecida
  Profissão                                  | Pedagoga
  Escolaridade                               | Superior Completo
  Nível de conhecimentos sobre o aplicativo  | Conhecia o aplicativo e já tinha utilizado para verificar a situação do seu carro, mas nunca utilizou as demais funcionalidades dispostas pelo aplicativo.
  História de contexto                      |  Aparecida é professora de ensino infantil e ama o seu trabalho. Ela é casada e possui 3 filhos. Ao estar passeando com a sua família em um parque de diversões, um dos seus filhos (que possui apenas 5 anos) se perdeu dela e do restante da família. Aparecida não sabe exatamente o que aconteceu. Ela compareceu à administração do parque para informar o ocorrido e depois às autoridades. Ninguém parece saber o que aconteceu, mas todos suspeitam de sequestro. Como Aparecida sabe que o aplicativo Sinesp possui como uma das suas funcionalidades a visualização de pessoas desaparecidas, ela entra diariamente no aplicativo para ver se seu filho aparece nesta lista para que ela possa inserir uma foto dele com seus respectivos dados.
  Sugestão para melhoria                     | Sem sugestão.

### **Requisitos Elicitados (Introspecção - 3)** 

** **

 Código  | Descrição |  Prioridade
  :--------- | :------: | :------
  RF01   |  Acessar lista de desaparecidos             | Must
  RF02   |  Adicionar foto para a pessoa desaparecida  | Should

**Versionamento**

Código  | Descrição |  Prioridade  | Autor 
  :--------- | :------: | :------: | :------
  Versão  |  Data           |  Modificação                   |  Autor
  **0.1** |  **15/09/2020** |  **Adição da introspecção**    |  **Todos**
  **0.2** |  **24/09/2020** |  **Adição de outras personas** |  **Fellipe Araujo**

**Brainstorming**
-----------------

O **brainstorming** é uma técnica que visa o compartilhamento espontâneo
de idéias e a busca por ideias ou soluções. O termo em inglês significa
“tempestade de ideias”. Essa metodologia/técnica objetiva explorar as
ideias de um grupo de pessoas a fim de obter as melhores soluções.
Normalmente utiliza-se essa técnica bem no início, quando não há muito
conhecimento do produto, do processo e do projeto. Uma sessão bem
sucedida de Brainstorming acorda um conjunto de boas ideias, no qual os
participantes sentem que cada um contribuiu de alguma maneira para a
solução do problema.

Brainstorm V1
-------------

** **


BRAINSTORM  |  ** **
  :--------- | :------ 
  Data        | 15/09/2020
  Local       | Remoto
  Objetivo    | Trazer pensamentos inovadores em busca da resolução de problemas
  Descrição   | Foi unido todos os membros do grupo, todos compartilharam o máximo de ideias possíveis de forma espontânea. Nenhuma ideia sugerida foi descartada, todas foram anotadas e consideradas pela equipe.

** **

**Abaixo segue uma transcrição das principais ideias levantadas durante
a reunião.**

●       PB: O usuário tem fácil acesso a várias informações de segurança
nacional. Além disso, é fornecido de forma muito rápida todas as
informações que o usuário deseja.

●       IG: O usuário tem a possibilidade pesquisar rapidamente um
funcionário ou pessoa se tem alguma pendência com a justiça.

●       FA: O usuário pode fazer uma busca de um carro informando a
placa do mesmo e, assim, verificar a situação do carro
(roubado/furtado). O usuário ainda pode registrar pelo aplicativo o seu
carro como roubado/furtado.

### **Requisitos Elicitados (Brainstorming)**

#### **Requisitos Funcionais**

** **

   Código  | Descrição |  Prioridade
  :--------- | :------: | :------
  **RF01**  | **oferecer informações de prisão aguardando comprimento**                             |  **Must**
  **RF02**  | **O aplicativo deve oferecer informações de roubo ou furto de qualquer veículo.**      | **Must**
  **RF03** |  **O aplicativo deve alertar situação de roubo ou furto.**                             |  **Should**
  **RF04**  | **Consultar pessoas desaparecidas.**                                                  |  **Must**
  **RF05**  | **Exibir a lista dos criminosos mais procurados pelo país.**                           | **Should**
  **RF06**  | **As seções para cada parte do aplicativo deve ter uma boa interação com o usuário.**  | **Must**
  **RF07** |  ** **                                                                                   ** **

** **

#### **Requisitos Não Funcionais** 

 Código  | Descrição |  Prioridade
  :--------- | :------: | :------
  **RNF01**  | **Rapidez na pesquisa ao banco de dados**  | **Must**
  **RNF02**  | **Com restrição no número de pesquisa**    | **Would**
  **RNF03**  | **Base de dados atualizada**               | **Must**
  **RNF04**  | **Confiabilidade dos dados**               | **Must**
  **RNF05**  | **Página de suporte**                      | **Should**

** **

**Versionamento**

** **

  Código  | Descrição |  Prioridade  | Autor 
  :--------- | :------: | :------: | :------
  **1.0**  | **15/09/2020**  | **Adição do Brainstorming**  | **Todos**

** **

Técnicas de Priorização {#tecnicas-de-priorizacao}
-----------------------

Essa atividade consiste basicamente em determinar quais requisitos
possuem mais importância dentro do escopo do projeto, levando em
consideração não somente o ponto de vista do desenvolvedor mas
principalmente do ponto de vista do cliente para que a equipe possa dar
uma atenção maior para esses aspectos dentro do sistema.

### **MoSCoW:**

**      **O MoSCoW é uma das técnicas mais simples existentes quando o
assunto é priorização de requisitos. Ela consiste basicamente em dividir
esses requisitos em quatro categorias diferentes: Must (M), Should (S),
Could (C), Would (W). Sendo assim, para cada requisito do backlog é
atribuída uma dessas quatro categorias.

**Must:** São os requisitos prioritários/críticos. Na maioria das vezes
eles estão relacionados a normas legais (Business Requirement e Business
Rules), isto é, ligados a regra de negócios. Requisitos também que se
não forem implementados o sistema como um todo não pode ser avaliado
como concluído.

**Should:** São aquelas funcionalidades que, vistas de um ponto
estratégico, não precisam ser implementadas com urgência, para o
primeiro momento. Normalmente, funcionalidades que podem ser
reaproveitadas ou que o desenvolvimento de um outro projeto futuramente
acabe economizando e aumentando a reutilização do código para o projeto
em questão são avaliadas como “Should” também.

**Could:** Funcionalidades neste nível são aquelas que são desejáveis,
porém não necessárias e que a depender da disponibilidade de recursos da
empresa podem melhorar a satisfação do cliente.

**Would:** São os requisitos que não possuem muito retorno envolvido
para o projeto, mas que em concordância com o cliente podem ser
realizados, melhorando ainda mais o sistema.

As **vantagens** de aplicar o MoSCoW é que ela é uma técnica muito
simples e por isso as pessoas que desconhecem conseguem facilmente
aprender e aplicar. As **desvantagens** é que ela possui um viés muito
subjetivo, onde cada pessoa pode acabar determinando uma determinada
prioridade para o mesmo requisito, e também tende a dar mais atenção e
importância para os requisitos mais políticos, como citado em “Must”,
além do cliente ter que demonstrar um bom conhecimento daquilo que ele
deseja.

** **

**Versionamento**

** **

  Código  | Descrição |  Prioridade  | Autor 
  :--------- | :------: | :------: | :------
  **1.0**  | **15/09/2020**  | **Adição do Brainstorming**  | **Todos**

** **

** **


