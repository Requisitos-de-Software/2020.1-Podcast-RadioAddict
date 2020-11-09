# Léxicos - Verificação

## Introdução

Este documento tem como objetivo relatar a detecção de defeitos nos artefatos referentes aos Léxicos produzidos pelo grupo durante a etapa de modelagem. Para este fim, a utilização de um checklist mostrou-se a maneira mais clara e eficaz para encontrar possíveis falhas. Nos checklists elaborados, buscou-se uma forma de padronizar a verificação dos artefatos requeridos, utilizando questões pertinentes para o conjunto.

## Rastreabilidade

[Léxico](../../Modeling/lexicons.md)

## Inspeção 

| Questão 	| Justificativa 	|
|-	|-	|
|  Possui titulo ?  	| Identificar o título para uma melhor leitura 	|
|  Possui classificação correta ? 	| Classificação  para facilitar a visualização e rastreabilidade 	|
| Usa linguagem compreensível? 	| Deixar a leitura fluida 	|
| possui sinônimos corretos ? 	| O léxico deve ter sinônimos para facilitar a compreensão  	|
| possui impacto correto? 	| Entender cada léxico facilmente  	|
| As informaçoes sao o suficiente para entender o léxico? 	| Se há informações suficiente para entender o léxico 	|
| Segui a ordem dos dados estabelecidos ? 	| se os dados estão de acordo com cada léxico apresentado  	|
| possui rastreabilidade ? 	| Para facilitar a rastreabilidade 	|
| possui versionamento ? 	| É possível identificar a versão apresentada  	|



## Checklist

| Questões 	| L01 	| l02 	| L03 	| L04 	| L05 	| L06 	| L07 	| L08 	|
|-	|-	|-	|-	|-	|-	|-	|-	|-	|
| 1 Possui titulo ?  	| ✔ 	| ✔ 	| ✔ 	| ✔ 	| ✔ 	| ✔ 	| ✔ 	| ✔ 	|
| 2 Usar linguagem compreensível? 	| ✔ 	| ✔ 	| ✔ 	| ✔ 	| ✔ 	| ✔ 	| ✔ 	| ✔ 	|
| 3 Possu classificação correta ? 	| ✔ 	| ✔ 	| ✔ 	| ✔ 	| ✔ 	| ✔ 	| ✔ 	| ✔ 	|
| 4 Possui sinônimos corretos ? 	| ✔ 	| ✔ 	| ✔ 	| ✔ 	| ❌ 	| ✔ 	| ❌ 	| ✔ 	|
| 5 Possui impacto correto? 	| ✔ 	| ✔ 	| ✔ 	| ✔ 	| ✔ 	| ✔ 	| ✔ 	| ✔ 	|
| 6 As informaçoes sao o suficiente para entender o léxico? 	| ✔ 	| ✔ 	| ✔ 	| ✔ 	| ✔ 	| ✔ 	| ✔ 	| ✔ 	|
| 7 Segui a ordem dos dados estabelecidos ? 	| ✔ 	| ✔ 	| ✔ 	| ✔ 	| ✔ 	| ✔ 	| ✔ 	| ✔ 	|
| 8 Possui rastreabilidade ?nenhum 	| ❌ 	| ❌ 	| ❌ 	| ❌ 	| ❌ 	| ❌ 	| ❌ 	| ❌ 	|
| 9 Possui versionamento ? 	| ✔ 	| ✔ 	| ✔ 	| ✔ 	| ✔ 	| ✔ 	| ✔ 	| ✔ 	|


## Observações

| L 	| Observações 	|
|-	|-	|
| Todos 	| - Revisar todos os léxicos e adicionar rastreabilidade onde seja necessário, ajudando no versionamento 	|
| L05 	| Sinônimo Estranho 	|
| L07  	| Escolher outro sinônimo  	|
| L06 	| Adicionar mais sinônimos  	|

## Conclusão

O caso de uso estar de acordo com os critérios de qualidade estabelecidos,Apenas alguns detalhes devem ser refatorados.
. A falha mais notável nos modelos foi a falta de rastreabilidade, juntamente com vários casos em que  estavam errados. As causas prováveis são: questões de tempo, atenção ou alinhamento com os outros membros.

  ## Referências
[Página de verificação dos Cenários do grupo Audible - 2019.2](https://requisitos-de-software.github.io/2019.2-Audible/verificacao_cenarios/)


## Versionamento
Data | Versão | Descrição | Autor 
------ | --------- | ---------- | --------
08/11/2020 | 1.0 | Verificação dos Léxicos | Itallo