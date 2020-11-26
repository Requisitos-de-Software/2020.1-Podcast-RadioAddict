# Matriz backward-from

## Introdução

A rastreabilidade de requisitos é uma característica de sistemas nos quais 
requisitos são claramente ligados às suas fontes e aos artefatos criados 
durante o ciclo de vida de desenvolvimento do sistema baseado nesses requisitos.
Rastreabilidade de requisitos estabelece um elo entre mudanças das necessidades
dos usuários e evolução dos sistemas de computação, sendo uma base para o
gerenciamento do conhecimento organizacional.

## Meta-Modelo de Toranzo

A literatura apresenta diversos trabalhos enfocando os tipos de relacionamentos
associados à rastreabilidade. A meta-modelo de Toranzo foi escolhido para o
projeto do grupo.</br>
A proposta de Toranzo para a rastreabilidade utiliza quatro estratégias de trabalho:
apresenta uma classificação das informações a serem rastreadas, propõe uma meta-modelo
para a rastreabilidade e um modelo intermediário para o rastreamento de requisitos
e ainda inclui um processo para guiar o engenheiro de requisitos na aplicação das
outras três estratégias. As informações a serem rastreadas seriam classificadas em
quatro níveis: ambiental, organizacional, gerencial e desenvolvimento.

- **Ambiental:** congrega informações oriundas do contexto ambiental onde a organização
está inserida e que podem afetar o sistema sendo desenvolvido;
- **Organizacional:** reúne informações relacionadas à organização (missão, objetos, metas e
padrões) e que podem impactar os requisitos do sistema;
- **Gerencial:** agrega informações que permitem associar tarefas a requisitos, e que
podem auxiliar a gerência do projeto;
- **Desenvolvimento:** contém informações relacionadas aos diversos artefatos gerados
no processo de desenvolvimento.

Neste meta-modelo possui suporte à rastreabilidade identifica os seguintes tipos de elos:

- **Satisfação:** indica que a classe de origem tem dependência de satisfação com classe
destino;
- **Recurso:** indica que a classe de origem tem dependência de recurso com classe de
destino;
- **Responsabilidade:** registra a participação, responsabilidade e ação de pessoas
sobre artefatos;
- **Representação:** captura a representação ou modelagem dos requisitos em outras
linguagens;
- **Alocado:** classe de origem está relacionada à classe de destino, que representa
um subsistema;
- **Agregação:** indica composição de elementos.

Id | Requisito | Artefato | Tipo | Categoria meta-modelo | Elo
---|-----------|----------|------|-----------------------|----
[**R01** ](https://requisitos-de-software.github.io/2020.1-Sinesp/Elicitation/brainstorming/) | Oferecer informações de prisão aguardando cumprimento | US06, US07 | Funcional | Ambiental | Recurso
[**R02**](https://requisitos-de-software.github.io/2020.1-Sinesp/Elicitation/brainstorming/) | O aplicativo deve oferecer informações de roubo ou furto de qualquer veículo. | US04, US05 | Funcional | Ambiental; Organizacional | Recurso
[**R03**](https://requisitos-de-software.github.io/2020.1-Sinesp/Elicitation/brainstorming/) | O aplicativo deve alertar situação de roubo ou furto. | US04, US05 | Funcional | Ambiental; Organizacional | Responsabilidade; Recurso
[**R04**](https://requisitos-de-software.github.io/2020.1-Sinesp/Elicitation/brainstorming/) | Consultar pessoas desaparecidas  | US08 | Funcional | Ambiental; Organizacional | Recurso; Responsabilidade
[**R05**](https://requisitos-de-software.github.io/2020.1-Sinesp/Elicitation/brainstorming/) | Exibir a lista dos criminosos mais procurados pelo país. | US11 | Funcional | Ambiental; Organizacional | Recurso; Responsabilidade
[**R06**](https://requisitos-de-software.github.io/2020.1-Sinesp/Elicitation/brainstorming/) | As seções para cada parte do aplicativo deve ter uma boa interação com o usuário. | Diagrama de desempenho | Funcional | Organizacional; Desenvolvimento | Responsabilidade
[**R07**](https://requisitos-de-software.github.io/2020.1-Sinesp/Elicitation/brainstorming/) | Rapidez na pesquisa ao banco de dados  | Diagrama de desempenho | Não Funcional | Organizacional; Desenvolvimento | Satisfação; Recurso
[**R08**](https://requisitos-de-software.github.io/2020.1-Sinesp/Elicitation/brainstorming/) | Com restrição no número de pesquisa  | Diagrama de desempenho | Não Funcional | Organizacional; Desenvolvimento | Recurso
[**R09**](https://requisitos-de-software.github.io/2020.1-Sinesp/Elicitation/brainstorming/) |  Base de dados atualizada frequentemente  | Diagrama de usabilidade | Não Funcional | Ambiental; Organizacional; Desenvolvimento | Agregação; Responsabilidade; Alocado
[**R10**](https://requisitos-de-software.github.io/2020.1-Sinesp/Elicitation/brainstorming/) | Confiabilidade dos dados | Diagrama de segurança | Não Funcional | Ambiental; Organizacional | Agregação; Responsabilidade;
[**R11**](https://requisitos-de-software.github.io/2020.1-Sinesp/Elicitation/brainstorming/) | Página de suporte  | <i></i> | Não Funcional | Organizacional | Recurso Satisfação
[**R12**](https://requisitos-de-software.github.io/2020.1-Sinesp/Elicitation/brainstorming/) | Busca de veículo informando se a placa é do mercosul ou não  | <i></i> | Não Funcional | Ambiental; Organizacional; Desenvolvimento | Recurso
[**R13**](https://requisitos-de-software.github.io/2020.1-Sinesp/Elicitation/brainstorming/) | Busca de desaparecidos por filtro  | US09 | Não Funcional | Organizacional; Desenvolvimento | Recurso
[**R14**](https://requisitos-de-software.github.io/2020.1-Sinesp/Elicitation/brainstorming/) | Busca de mandados por filtro  | US07 | Não Funcional | Organizacional; Desenvolvimento | Recurso
[**R15** ](https://requisitos-de-software.github.io/2020.1-Sinesp/Elicitation/brainstorming/) | Multiplataforma (Android, IOS, Tablets)  | <i></i> | Não Funcional | Organizacional; Desenvolvimento | Alocado; Representação; Agregação
[**R16**](https://requisitos-de-software.github.io/2020.1-Sinesp/Elicitation/introspection/) | Realizar pesquisas sucessivas  | Diagrama de Usabilidade | Não Funcional | Organizacional; Desenvolvimento | Recurso
[**R17**](https://requisitos-de-software.github.io/2020.1-Sinesp/Elicitation/introspection/) | Realizar cadastro de carro roubado/furtado  | <i></i> | Funcional | Ambiental;Organizacional; Desenvolvimento | Satisfação; Recurso; Responsabilidade
[**R18**](https://requisitos-de-software.github.io/2020.1-Sinesp/Elicitation/introspection/) | Adicionar foto para a pessoa desaparecida  | <i></i> | Funcional| Ambiental;Organizacional; Desenvolvimento | Satisfação; Recurso; Responsabilidade

## Referências

[Sayão, Miriam. Leite, Julio Cesar Sampaio do Prado. **Rastreabilidade de Requisitos**.Monografia. 2005. PUC-RIO](https://aprender3.unb.br/mod/resource/view.php?id=70621) Acesso em: 25/11/2020

[SERRANO, Maurício; SERRANO, Milene; Requisitos – Aula 26 Elicitação, Modelagem, Análise.](https://aprender3.unb.br/pluginfile.php/426777/mod_resource/content/1/Requisitos%20-%20Aula%20026.pdf) Acesso em: 25/11/2020

[Aula 25 - Apoio: Pós-Rastreabilidade - Gerência II](https://www.youtube.com/watch?v=2vokkbYeX8U&feature=youtu.be&ab_channel=Andr%C3%A9BarrosdeSales) Acesso em: 25/11/2020

## Versionamento

Data | Versão | Descrição | Autor
------ | --------- | ---------- | --------
25/11/2020 | 1.0 | Documentação da matriz forward-from | Rafael Ribeiro
