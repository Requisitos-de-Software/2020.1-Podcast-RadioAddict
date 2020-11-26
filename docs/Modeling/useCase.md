### Introdução
Casos de Uso são utilizados para descrever um conjunto de ações que um sistema ou um conjunto de sistemas deve desempenhar em colaboração com um ou mais usuários externos ao sistema. Essa descrição é feita a partir de um Diagrama de casos de uso em conjuntos com as especificações dos casos, onde é possível observar uma breve descrição e um fluxo de utilização de cada caso.


### Mandados

![UseCaseMandado](../Images/mandado_prisao.png)

Sigla | Definição
----- | ---------
Versão | 1.0
Autor | Todos
Descrição | Buscar por mandados de prisão
Ator | Policial/Cidadão
Pré-condições | Usuário ter acesso ao aplicativo
Fluxo Principal | - Usuário ter acesso o Sinesp</br> - Usuário busca pelo nome ou apelido da pessoa
Fluxo Alternativo | Não existe
Fluxo de Excessões | **FE1 - Sem conexão com a internet**<br/> - O aplicativo exibe a mensagem "Não foi possível identificar sua localização, já que não existe conexão com a internet"</br> **FE2-Nenhum resultado da pesquisa**</br> - O aplicativo mostra nada para o usuário.
Pós-condições | Usuário ver os mandados que pesquisou
Rastreabilidade | Baseado no requisito funcional 01 - Oferecer informações de prisão aguardando comprimento

### Desaparecidos

![UseCaseDesaparecido](../Images/desaparecidos.png)

Sigla | Definição
----- | ---------
Versão | 1.0
Autor | Todos
Descrição | Buscar por desaparecidos
Ator | Policial/Cidadão
Pré-condições | Usuário ter acesso ao aplicativo
Fluxo Principal | - Usuário ter acesso o Sinesp</br> - Usuário seleciona uma pessoa da lista
Fluxo Alternativo | Não existe
Fluxo de Excessões | **FE1 - Sem conexão com a internet**<br/> - O aplicativo exibe a mensagem "Não foi possível identificar sua localização, já que não existe conexão com a internet"</br> **FE2-Nenhum resultado da pesquisa**</br> - O aplicativo mostra nada para o usuário.
Pós-condições | Usuário ver os desaparecidos
Rastreabilidade | Baseado no requisito funcional 04 - Consultar pessoas desaparecidas.

### Consultar

![UseCaseDesaparecido](../Images/consultar_registro.png)

Sigla | Definição
----- | ---------
Versão | 1.0
Autor | Todos
Descrição | Consultar registro de roubo de um carro
Ator | Policial/Cidadão
Pré-condições | Usuário ter acesso ao aplicativo
Fluxo Principal | - Usuário ter acesso o Sinesp</br> - Usuário insere as informações da placa do veículo
Fluxo Alternativo | Não existe
Fluxo de Excessões | **FE1 - Sem conexão com a internet**<br/> - O aplicativo exibe a mensagem "Não foi possível identificar sua localização, já que não existe conexão com a internet"</br> **FE2-Nenhum resultado da pesquisa**</br> - O aplicativo mostra nada para o usuário.
Pós-condições | Usuário ver o veículo que pesquisou
Rastreabilidade | Baseado no requisito funcional 02 - O aplicativo deve oferecer informações de roubo ou furto de qualquer veículo.

## Versionamento
Data | Versão | Descrição | Autor 
------ | --------- | ---------- | --------
08/10/2020 | 1.0 | Criação do Use Case | Paulo
08/10/2020 | 1.1 | Revisão | Itallo
25/11/2020 | 2.0 | mar autore, introdução | itallo