# NFR - Verificação

## Introdução

Este documento tem como objetivo analisar e relatar se os artefatos dos NFR's foram elaborados de forma correta e coerente. Para isso, foi utilizada a técnica de inspeção. Foi definida uma checklist, onde cada tópico foi avaliado e os defeitos detectados foram descritos para que possam ser corrigidos posteriormente.

## Rastreabilidade

[NFR](../../Modeling/NFRFramework.md)

## Inspeção

Questão | Justificativa
------- | -------------
Os softgoals representam metas que não têm definições claras? | Um softgoal representa uma meta que não tem uma definição clara e/ou critérios sobre se é satisfeita ou não
Softgoals são decompostos em operacionalizações? | Todo softgoal deve se decompor em uma ou mais operacionalizações, e os sentidos das setas que os ligam devem ser debaixo para cima.
Os relacionamentos entre os softgoals expressam as relações de influência e interdependência de uns com os outros? | Os objetivos programáticos são relacionados por meio de relacionamentos que representam a influência ou interdependência de um softgoal em outro.
Para cada softgoal, existem mais evidências positivas do que evidências negativas? | Diz-se que um softgoal é "satisfeito" quando há evidência positiva e pouca evidência negativa contra ela.
Os objetivos foram decompostos em uma hierarquia com AND/OR de softgoals? | Os objetivo do NFR devem ser decompostos em um hierarquia de operacionalizações and/or.
Os objetivos mais críticos foram devidamente marcados/sinalizados? | Objetivos críticos devem ser sinalizados com '!' e mais críticos com '!!'.
Os graus de satisfação foram indicados? | A satisfação ocorre em 4 intensidades: '++'(muito satisfeito), '+'(satisfeito), '-'(insatisfeito), '--'(muito insatisfeito).
O sentido das setas que ligam os softgoals é coerente? | As operacionalizações devem se ligar aos softgoals, e as setas devem ter este sentido
As linhas tracejadas e contínuas foram utilizadas corretamente? | As setas com linhas continuas indicam a relação de interdependência implicita e as pontilhadas as relações explícitas.

## Checklist

Questões | NFR Usabilidade | NFR Confiabilidade
-------- | --------------- | ------------------
Os softgoals representam metas que não têm definições claras? | ✔ | ✔
Softgoals são decompostos em operacionalizações? | ❌ | ❌
Os relacionamentos entre os softgoals expressam as relações de influência e interdependência de uns com os outros? | ✔ | ✔
Para satisfazer o softgoal, existem mais evidências positivas do que evidências negativas? | ✔ | ✔
Os objetivos foram decompostos em uma hierarquia com AND/OR de softgoals? | ❌ | ❌
Os objetivos mais críticos foram devidamente marcados/sinalizados? | ❌ | ❌
Os graus de satisfação foram indicados? | ❌ | ❌
O sentido das setas que ligam os softgoals é coerente? | ❌ | ❌
As linhas tracejadas e contínuas foram utilizadas corretamente? | ❌ | ❌

## Observações

NFR     | Observações
------- | -----------
Usabilidade | <ul><li>Não são todos os softgoals que estão decompostos em operacionalizações, eles devem ser decompostos em pelo menos um.</li><li>Os softgoals devem ser decompostos em hierarquias AND/OR. No momento, não há essa decomposição.</li><li>Não possui nenhuma indicação se os objetivos são críticos ou não.</li><li>Não possui nenhuma indicação de grau de satisfação.</li><li>O sentido das setas não está sendo indicado na ligação com os softgoals.</li><li>As linhas não foram utilizadas de forma coerente, tendo a ausência das linhas tracejadas que demonstram as relações explícitas.</li></ul>
Confiabilidade | <ul><li>Não são todos os softgoals que estão decompostos em operacionalizações, eles devem ser decompostos em pelo menos um.</li><li>Os softgoals devem ser decompostos em hierarquias AND/OR. No momento, não há essa decomposição.</li><li>Não possui nenhuma indicação se os objetivos são críticos ou não.</li><li>Não possui nenhuma indicação de grau de satisfação.</li><li>O sentido das setas não está sendo indicado na ligação com os softgoals.</li><li>As linhas não foram utilizadas de forma coerente, tendo a ausência das linhas tracejadas que demonstram as relações explícitas.</li></ul>

## Conclusão

Com base da utilização da Verificação e o uso da checklist, pode-se concluir que os artefatos analisados possuem inconsistências que devem ser corrigidas, tais como: softgoals não decompostos em operacionalizações, ausência de hierarquias AND/OR, ausência da indicação de objetivos críticos, ausência da indicação de grau de satisfação, o sentido das setas está de forma incoerente, entre outros.

## Referências

[Página de Verificação dos NFRs do grupo Waze - 2019.2](https://requisitos-de-software.github.io/2019.2-Waze/Verificacao-NFR/)

[SERRANO, Maurício; SERRANO, Milene; Requisitos – Aula 17](https://aprender3.unb.br/pluginfile.php/426768/mod_resource/content/1/Requisitos%20-%20Aula%20019a.pdf)

[SERRANO, Maurício; SERRANO, Milene; Requisitos – Aula 23](https://aprender3.unb.br/pluginfile.php/426773/mod_resource/content/2/Requisitos%20-%20Aula%20023.pdf)

## Versionamento
Data | Versão | Descrição | Autor 
---- | ------ | --------- | --------
08/11/2020 | 1.0 | Verificação dos NFRs de Confiabilidade e Usabilidade | Fellipe