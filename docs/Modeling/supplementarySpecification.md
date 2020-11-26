### Introdução
<p style="text-align: justify;"> &emsp;&emsp;
Uma especificação suplementar lista os requisitos não-funcionais do sistema, junto com as outras técnicas de modelagem e elicitação utilizadas é possível capturar o conjunto completo de requisitos do sistema.
</p>

### Escopo
<p style="text-align: justify;"> &emsp;&emsp;
O Sinesp Cidadão é um aplicativo de acesso público, que visa aproximar o cidadão das políticas e ações de segurança pública, permitindo aos seus usuários realizarem consultas sobre Mandados de Prisão, Veículos com Restrições (Roubo e Furto), Pessoas Desaparecidas e Procurados pela Justiça.
</p>

### Finalidade
<p style="text-align: justify;"> &emsp;&emsp;
A Especificação Suplementar tem como finalidade definir os requisitos não funcionais do aplicativo Sinesp Cidadão que não foram explicitados nas outras técnicas de modelagem de requisitos.
</p>

## Descrição dos Requisitos não Funcionais
Código | Descrição
------ | ----------
RNF01 | Rapidez na pesquisa ao banco de dados
RNF02 | Restrição no número de pesquisas
RNF03 | Base de dados atualizada frequentemente
RNF04 | Confiabilidade dos dados
RNF05 | Página de suporte
RNF06 | Busca de veículo informando se a placa é do mercosul ou não
RNF07 | Busca de desaparecidos por filtro
RNF08 | Busca de mandados por filtro
RNF09 | Multiplataforma (Android, IOS, Tablets)

### Visão Geral
<p style="text-align: justify;"> &emsp;&emsp;
Este documento apresenta uma introdução ao Sinesp Cidadão a fim de deixar claro o escopo do projeto. Para isso, foi utilizado o um modelo para classificação de atributos de qualidade de software, denominado FURPS+ (Funcionalidade, Usabilidade, Confiabilidade, Performance, Suportabilidade).
</p>

## Funcionalidades
<p style="text-align: justify;"> &emsp;&emsp;
As funcionalidade já elicitadas até o momento podem ser encontradas por toda a documentação já elaboradas pelo grupo.
</p>

## Usabilidade
* **O usuário pode acessar o histórico facilmente na tela de busca de veículos, desaparecidos e mandados para selecionar uma pesquisa já realizada.**
    * Acessando o histórico, o usuário pode selecionar uma pesquisa já realizada, não sendo necessário digitar todas as informações nos campos de busca para realizar sua busca.
* **Facilidade de busca.**
    * Para desaparecidos e mandados, o aplicativo deve ter um filtro para restringir as buscas e retornar uma menor quantidade de dados.
* **Linguagem adequada ao perfil de usuário (cidadão comum e servidores públicos da justiça).**
    * Dependendo de qual seção foi acessada, a página deve possuir uma linguagem adequada para tal. Para páginas de mais uso do cidadão comum como, por exemplo, busca por veículos e por desaparecidos, possui uma linguagem de mais fácil entendimento em relação as páginas de mais uso de servidores públicos da justiça como mandados e lista de procurados.
* **O aplicativo é multiplataforma.**
    * É possível acessá-lo em dispositivos Android, IOS e Tablets.

## Confiabilidade
* **Segurança de Dados.**
    * Para a lista de desaparecidos, a adição de uma foto para tal pessoa só deve ser permitida caso o usuário esteja logado com uma conta gov.br, permitindo, assim, que a foto não seja adicionada/alterada por qualquer pessoa.
* **Disponibilidade.**
    * Os servidores e base de dados do aplicativo devem mantê-lo disponível e atualizado frequentemente para que, assim, seja possível realizar buscas e obter dados atualizados.
    * O sistema deve assegurar pesquisas taxa de erro: 1 caso em 100.

## Performance
* **Tempo de resposta na busca na base de dados.**
    * Tempo de resposta: o tempo de resposta do aplicativo deve ser de no máximo 10 segundos.
    * O tempo de resposta da requisição de uma busca ou inserção de dados deve ser rápida ou, na melhor das hipóteses, instantânea, já que caso haja um furto ou roubo de carro, ou alguém suspeito seja visto em local público, ou um desaparecido possa ter sido reconhecido, seja possível ter acesso a base de dados.
    * Dependabilidade do sistema: caso ocorra a perda da conexão do sistema com o banco de dados do governo nenhuma ferramenta irá funcionar. 


## Suportabilidade
<p style="text-align: justify;"> &emsp;&emsp;
A aplicação está disponível em todas as plataformas: Android (4.1.xou superior ), iOS(iOS 9.0 ou superior) e Navegadores. 
</p>

### Referências
[Sinesp: Site da Justiça e Segurança Pública – Sinesp Cidadão](https://www.justica.gov.br/sua-seguranca/seguranca-publica/sinesp-1/sinesp-Cidadao)

[SERRANO, Maurício; SERRANO, Milene; Requisitos – Aula 13](https://aprender3.unb.br/pluginfile.php/426751/mod_resource/content/1/Requisitos%20-%20Aula%20013a.pdf)

## Versionamento
Data | Versão | Descrição | Autor
---- | ------ | --------- | -----
08/10/2020 | 1.0 | Criação da Especificação Suplementar | Fellipe
25/11/2020 | 2.0 | Arrumando pontos do feedback | itallo