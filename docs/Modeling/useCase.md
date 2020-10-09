### Mandados
** **

<center>
![Mandato](../Images/mandado_prisao.png)
</center>

| Sigla              | Definição                                                    |
| ------------------ | ------------------------------------------------------------ |
| Versão             | 1.0                                                          |
| Autor              | Todos                                                        |
| Descrição          | Buscar por mandados de prisão                                |
| Ator               | Sinesp  e Usuários                                           |
| Pré-condições      | Usuário ter acesso ao aplicativo                             |
| Fluxo principal    | - Usuário acesso o Sinesp<br>- Usuário busca pelo nome ou apelido da pessoa |
| Fluxo alternativo  | Não existe                                                   |
| Fluxo de excessões | **FE1 - Sem conexão com a internet**  <br>- O aplicativo exibe a mensagem "Não foi possível identificar sua localização, já que não conexão com a internet"  **<br>FE2-Nenhum resultado da pesquisa**   <br>- O aplicativo mostra nada para  o usuário. |
| Pós condições      | Usuário ver os mandados que pesquisou                        |
| Rastreabilidade    | Baseado no requisito funcional 01 - Oferecer informações de prisão aguardando comprimento. |
** **

### Desaparecidos

** **

<center>
![Desaparecidos](../Images/desaparecidos_v2.png)
</center>

| Sigla              | Definição                                                    |
| ------------------ | ------------------------------------------------------------ |
| Versão             | 1.0                                                          |
| Autor              | Todos                                                        |
| Descrição          | Buscar por desaparecidos                                     |
| Ator               | Sinesp <br>Usuários                                          |
| Pré-condições      | Usuário ter acesso ao aplicativo                             |
| Fluxo principal    | - Usuário acesso o Sinesp<br>- Usuário seleciona uma pessoa da lista |
| Fluxo alternativo  | Não existe                                                   |
| Fluxo de excessões | **FE1 - Sem conexão com a internet**<br>- O aplicativo exibe a mensagem "Não foi possível identificar sua localização, já que não conexão com a internet" <br> **FE2-Nenhum resultado da pesquisa**<br>- O aplicativo mostra nada para  o usuário. |
| Pós condições      | Usuário ver os desaparecidos                                 |
| Rastreabilidade    | Baseado no requisito funcional 04 - Consultar pessoas desaparecidas. |

### Consultar
** **
<center>
![Consultar](../Images/consultar_registro.png)
</center>

| Sigla              | Definição                                                    |
| ------------------ | ------------------------------------------------------------ |
| Versão             | 1.0                                                          |
| Autor              | Todos                                                        |
| Descrição          | Consultar registro de roubo de um carro                      |
| Ator               | Sinesp <br>Usuários                                          |
| Pré-condições      | Usuário ter acesso ao aplicativo                             |
| Fluxo principal    | - Usuário acesso o Sinesp <br>- Usuário insere as informações da placa do veículo |
| Fluxo alternativo  | Não existe                                                   |
| Fluxo de excessões | **FE1 - Sem conexão com a internet**   <br>- O aplicativo exibe a mensagem "Não foi possível identificar sua localização, já que não conexão com a internet" <br> **FE2-Nenhum resultado da pesquisa**<br>- O aplicativo mostra nada para  o usuário. |
| Pós condições      | Usuário ver o veículo que pesquisou                          |
| Rastreabilidade    | Baseado no requisito funcional 02 - O aplicativo deve oferecer informações de roubo ou furto de qualquer veículo. |


<center>

| Data               | Versão             | Descrição          | Autor              |
 |--------------------|--------------------|--------------------|--------------------|
| 08/10/2020         | 1.0                | Use Case | João             |
| 08/10/2020         | ** **                | Revisão | itallo             |

</center>