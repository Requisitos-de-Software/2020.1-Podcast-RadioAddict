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

Origem | ID | Requisito | Categoria da meta-modelo | Tipo de elo
-------|----|-----------|--------------------------|------------
[Brainstorming](https://requisitos-de-software.github.io/2020.1-Sinesp/Elicitation/brainstorming/), [Instrospecção](https://requisitos-de-software.github.io/2020.1-Sinesp/Elicitation/introspection/) | **R01** | Oferecer informações de prisão aguardando cumprimento | Ambiental | Representação
[Brainstorming](https://requisitos-de-software.github.io/2020.1-Sinesp/Elicitation/brainstorming/), [Instrospecção](https://requisitos-de-software.github.io/2020.1-Sinesp/Elicitation/introspection/) | **R02** | O aplicativo deve oferecer informações de roubo ou furto de qualquer veículo. | Ambiental; Organizacional | Representação
[Brainstorming](https://requisitos-de-software.github.io/2020.1-Sinesp/Elicitation/brainstorming/) | **R03** | O aplicativo deve alertar situação de roubo ou furto. | Ambiental; Organizacional | Representação
[Brainstorming](https://requisitos-de-software.github.io/2020.1-Sinesp/Elicitation/brainstorming/), [Instrospecção](https://requisitos-de-software.github.io/2020.1-Sinesp/Elicitation/introspection/) | **R04** | Consultar pessoas desaparecidas | Ambiental; Organizacional | Representação
[Brainstorming](https://requisitos-de-software.github.io/2020.1-Sinesp/Elicitation/brainstorming/), [Instrospecção](https://requisitos-de-software.github.io/2020.1-Sinesp/Elicitation/introspection/) | **R05** | Exibir a lista dos criminosos mais procurados pelo país. | Ambiental; Organizacional | Representação
[Brainstorming](https://requisitos-de-software.github.io/2020.1-Sinesp/Elicitation/brainstorming/) | **R06** | 	As seções para cada parte do aplicativo deve ter uma boa interação com o usuário. | Organizacional; Desenvolvimento | Representação
[Brainstorming](https://requisitos-de-software.github.io/2020.1-Sinesp/Elicitation/brainstorming/) | **R07** | Rapidez na pesquisa ao banco de dados | Organizacional; Desenvolvimento | Representação
[Brainstorming](https://requisitos-de-software.github.io/2020.1-Sinesp/Elicitation/brainstorming/) | **R08** | 	Com restrição no número de pesquisa | Organizacional; Desenvolvimento | Representação
[Brainstorming](https://requisitos-de-software.github.io/2020.1-Sinesp/Elicitation/brainstorming/) | **R09** | Base de dados atualizada frequentemente | Ambiental; Organizacional; Desenvolvimento | Representação
[Brainstorming](https://requisitos-de-software.github.io/2020.1-Sinesp/Elicitation/brainstorming/) | **R10** | Confiabilidade dos dados | Ambiental; Organizacional | Representação
[Brainstorming](https://requisitos-de-software.github.io/2020.1-Sinesp/Elicitation/brainstorming/) | **R11** | Página de suporte | Organizacional | Representação
[Brainstorming](https://requisitos-de-software.github.io/2020.1-Sinesp/Elicitation/brainstorming/) | **R12** | Busca de veículo informando se a placa é do mercosul ou não | Ambiental; Organizacional; Desenvolvimento | Representação
[Brainstorming](https://requisitos-de-software.github.io/2020.1-Sinesp/Elicitation/brainstorming/) | **R13** | Busca de desaparecidos por filtro | Organizacional; Desenvolvimento | Representação
[Brainstorming](https://requisitos-de-software.github.io/2020.1-Sinesp/Elicitation/brainstorming/) | **R14** | Busca de mandados por filtro | Organizacional; Desenvolvimento | Representação
[Brainstorming](https://requisitos-de-software.github.io/2020.1-Sinesp/Elicitation/brainstorming/) | **R15** | Multiplataforma (Android, IOS, Tablets) | Organizacional; Desenvolvimento | Representação
[Instrospecção](https://requisitos-de-software.github.io/2020.1-Sinesp/Elicitation/introspection/) | **R16** | Realizar pesquisas sucessivas | Organizacional; Desenvolvimento | Representação
[Instrospecção](https://requisitos-de-software.github.io/2020.1-Sinesp/Elicitation/introspection/) | **R17** | Realizar cadastro de carro roubado/furtado | Ambiental;Organizacional; Desenvolvimento | Representação
[Instrospecção](https://requisitos-de-software.github.io/2020.1-Sinesp/Elicitation/introspection/) | **R18** | Adicionar foto para a pessoa desaparecida | Ambiental;Organizacional; Desenvolvimento | Representação

## Referências

[Sayão, Miriam. Leite, Julio Cesar Sampaio do Prado. **Rastreabilidade de Requisitos**.Monografia. 2005. PUC-RIO](https://aprender3.unb.br/mod/resource/view.php?id=70621) Acesso em: 25/11/2020

[SERRANO, Maurício; SERRANO, Milene; Requisitos – Aula 26 Elicitação, Modelagem, Análise.](https://aprender3.unb.br/pluginfile.php/426777/mod_resource/content/1/Requisitos%20-%20Aula%20026.pdf) Acesso em: 25/11/2020

[Aula 25 - Apoio: Pós-Rastreabilidade - Gerência II](https://www.youtube.com/watch?v=2vokkbYeX8U&feature=youtu.be&ab_channel=Andr%C3%A9BarrosdeSales) Acesso em: 25/11/2020

## Versionamento

Data | Versão | Descrição | Autor
------ | --------- | ---------- | --------
25/11/2020 | 1.0 | Documentação da matriz backward-from | Rafael Ribeiro
