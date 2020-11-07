# Use Case - Verificação

## Introdução

Este documento tem como objetivo analisar e relatar se os artefatos dos casos de uso foram elaborados de forma correta e coerente. Para isso, foi utilizada a técnica de inspeção. Foi definida uma checklist, onde cada tópico foi avaliado e os defeitos detectados foram descritos para que possam ser corrigidos posteriormente.

## Rastreabilidade

[Use Case](../../Modeling/useCase.md)

## Inspeção

Questão | Justificativa
------- | -------------
A descrição de caso de uso condiz com o caso de uso representado no diagrama? | A imagem que representa o caso de uso deve estar de acordo com a descrição
A descrição de caso de uso possui nome do caso de uso e nome do ator? | A descrição deve possuir o nome do caso de uso e do ator
O Fluxo principal está explícito? | O fluxo principal deve estar evidenciado e distinto dos demais
O Caso de uso utiliza fluxos alternativos? | O caso de uso deve possuir fluxos alternativos, caso exista
As frases estão no tempo presente? | Os casos de uso utilizam por padrão frases que estão no presente
As frases representam um diálogo entre ator e sistema? | O entendimento do diagrama de casos de uso deve ser facilitado com esse diálogo
As frases possuem objetividade? | Para o caso de uso ser claro, as frases devem ser objetivas
As frases são construídas em voz ativa? | As frases, por padrão, devem representar uma ação do ator
As frases estão escritas corretamente de acordo com a norma padrão? | As frases devem estar de acordo com a norma da língua portuguesa
O caso de uso segue o padrão estabelecido? | Os modelos devem seguir um padrão estabelicido
O caso de uso possui o horário e a data de criação? | Para o caso de uso possuir uma boa rastreabilidade, deve possuir a data e hora de criação
O caso de uso possui rastreabilidade adequada? | Para facilitar na pós rastreabilidade,o caso de uso deve possuir uma rastreabilidade bem definida

## Checklist

Questões | UC00 | UC01 | UC02
-------- | ---- | ---- | ----
A descrição de caso de uso condiz com o caso de uso representado no diagrama? | ✔ | ✔ | ✔
A descrição de caso de uso possui nome do caso de uso e nome do ator? | ✔ | ✔ | ✔
O Fluxo principal está explícito? | ✔ | ✔ | ✔
O caso de uso utiliza fluxos alternativos? | ❌ | ❌ | ❌
As frases estão no tempo presente? | ❌ | ❌ | ❌
As frases representam um diálogo entre ator e sistema? | ✔ | ✔ | ✔
As frases possuem objetividade? | ✔ | ✔ | ✔
As frases são construídas em voz ativa? | ✔ | ✔ | ✔
As frases estão escritas corretamente de acordo com a norma padrão? | ✔ | ✔ | ✔
O caso de uso segue o padrão estabelecido? | ✔ | ❌ | ✔
O caso de uso possui o horário e a data de criação? | ❌ | ❌ | ❌
O caso de uso possui alguma rastreabilidade? | ✔ | ✔ | ✔

## Observações

UC   | Observações
---- | -----------
UC00 | <ul><li>Não foi apresentado fluxos alternativos, apesar de possuir na plataforma</li><li>Os verbos estão no presente, porém não seguem um padrão. Alguns estão no presente do indicativo e outros somente no infinitivo. Pode-se padronizar a conjugação dos verbos</li><li>O caso de uso foi criado sem indicar uma data e hora de sua criação</li></ul>
UC01 | <ul><li>Não foi apresentado fluxos alternativos, apesar de possuir na plataforma</li><li>Os verbos estão no presente, porém não seguem um padrão. Alguns estão no presente do indicativo e outros somente no infinitivo. Pode-se padronizar a conjugação dos verbos</li><li>O caso de uso não está seguindo o padrão estabelecido, apresentando algumas inconsistências. Um exemplo seria o sentido das setas colocadas de forma errada</li><li>O caso de uso foi criado sem indicar uma data e hora de sua criação</li></ul>
UC02 | <ul><li>Não foi apresentado fluxos alternativos, apesar de possuir na plataforma</li><li>Os verbos estão no presente, porém não seguem um padrão. Alguns estão no presente do indicativo e outros somente no infinitivo. Pode-se padronizar a conjugação dos verbos</li><li>O caso de uso foi criado sem indicar uma data e hora de sua criação</li></ul>

## Conclusão

Com base da utilização da Verificação e o uso da técnica de inspeção, pode-se concluir que os artefatos analisados possuem inconsistências que devem ser corrigidas, tais como: adição dos fluxos alternativos, padronização da conjugação verbal, adição de data e hora para a atualização dos casos de uso, alteração do sentido das setas, entre outros.

## Referências

[SERRANO, Maurício; SERRANO, Milene; Requisitos – Aula 13](https://aprender3.unb.br/pluginfile.php/426751/mod_resource/content/1/Requisitos%20-%20Aula%20013a.pdf)

[Lucidchart - Diagrama de caso de uso UML: O que é, como fazer e exemplos](https://www.lucidchart.com/pages/pt/diagrama-de-caso-de-uso-uml)

[UNIVESP - Gerência e Qualidade de Software - Verificação e Validação](https://www.youtube.com/watch?v=1Y-1zz6rZxo&feature=youtu.be&t=22)

## Versionamento
Data | Versão | Descrição | Autor 
---- | ------ | --------- | --------
07/11/2020 | 1.0 | Verificação dos Casos de Uso | Fellipe