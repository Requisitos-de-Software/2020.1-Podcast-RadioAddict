### C01 - Pesquisar Placa de Veículo
Título | Veículos
------ | --------
Objetivo | Obter informações sobre um veículo
Contexto | Local: Tela veículos; Pré-Condição: Ter instalado o app e ter GPS ativo; Pós-Condição: Usuário obtém informações sobre a legalidade do veículo
Atores | Usuário que quer obter informações sobre um veículo
Recursos | Internet, aplicativo instalado e placa do veículo a ser buscado.
Exceção | Internet cair, placa incorreta, servidor fora do ar.
Episódios | Usuário quer verificar a legalidade de um veículo, ativa o GPS e abre o aplicativo. Usuário clica no botão veículos. Usuário insere a placa do veículo. Usuário clica no botão buscar veículo. Os dados são mostrados com sucesso pelo Sinesp. Se o veículo não foi encontrado, usuário clica no botão ‘Tentar novamente’. Usuário clica no botão ‘Consultar outro veículo’ para obter informações sobre outro veículo

### C02 - Consultar Mandados de Prisão
Título | Mandados
------ | --------
Objetivo | Pesquisar mandado de prisão
Contexto | Local: Tela mandados; Pré-Condição: Ter instalado o app e GPS ativo; Pós-Condição: Usuário verifica se uma pessoa possui ou não mandado de prisão
Atores | Usuário que quer obter informações sobre uma pessoa que possui mandado
Recursos | Internet, aplicativo instalado e nome ou alcunha da pessoa a ser pesquisada
Exceção | Internet cair, nome ou alcunha inválido, servidor fora do ar.
Episódios | Usuário quer verificar se determinada pessoa possui um mandado de prisão, ativa o GPS e abre o aplicativo. Usuário clica no botão MANDADOS. Usuário marca ou não se vai colocar o apelido da pessoa procurada. Usuário insere o nome ou a alcunha da pessoa. Usuário clica no botão ‘Pesquisar por nome’ ou ‘Pesquisar por alcunha’. Os dados são mostrados com sucesso pelo Sinesp. Se a pessoa não foi encontrada, usuário clica no botão ‘Editar filtros’. Usuário clica no botão ‘Refinar busca’ para especificar mais a busca.

### C03 - Visualizar Lista de Desaparecidos
Título | Desaparecidos
------ | -------------
Objetivo | Visualizar a lista de pessoas desaparecidas
Contexto | Local: Tela desaparecidos; Pré-Condição: Ter instalado o app e ter GPS ativo; Pós-Condição: Usuário visualiza uma lista de pessoas desaparecidas
Atores | Usuário que quer consultar a lista de desaparecidos
Recursos | Internet, aplicativo instalado
Exceção | Internet cair, servidor fora do ar.
Episódios | Usuário quer consultar uma lista de pessoas desaparecidas, ativa o GPS e abre o aplicativo. Usuário clica no botão DESAPARECIDOS. A lista de desaparecidos é mostrada pelo Sinesp

### C04 - Ver a Lista de Procurados pela Justiça
Título | Procurados
------ | -------------
Objetivo | Consultar a lista de pessoas procuradas pela justiça
Contexto | Local: Tela procurados; Pré-Condição: Ter instalado o app e ter GPS ativo; Pós-Condição: Usuário visualiza uma lista de pessoas procuradas pela justiça
Atores | Usuário que quer consultar a lista de procurados
Recursos | Internet, aplicativo instalado
Exceção | Internet cair, servidor fora do ar.
Episódios | Usuário quer consultar a lista de pessoas procuradas pela justiça, ativa o GPS e abre o aplicativo. Usuário clica no botão PROCURADOS. A lista de procurados é disponibilizada pelo Sinesp

### C05 - Criar Conta
Título | Criar Conta
------ | ------------
Objetivo | Permitir que o usuário possua cadastro no aplicativo
Contexto | Local: Menu no canto superior esquerdo; Pré-Condição: Ter instalado o app e ter Internet; Pós-Condição: Usuário cria uma conta na aplicação
Atores | Usuário que deseja possuir cadastro na plataforma
Recursos | Internet, aplicativo instalado, número do CPF e conta de email
Exceção | Internet cair, servidor fora do ar, CPF inválido, email inválido
Episódios | Usuário quer se inscrever no aplicativo para salvar seus dados, abre o aplicativo. Usuário clica no menu que fica no canto superior esquerdo. Usuário clica no botão ‘Entrar na sua conta’. Usuário clica no botão ‘Crie sua conta’. Usuário escolhe uma das opções de cadastro. Usuário informa os dados pedidos pelo aplicativo. Usuário recebe a confirmação do cadastro no email

### C06 - Entrar
Título | Entrar
------ | ------
Objetivo | Entrar na conta do usuário
Contexto | Local: Menu no canto superior esquerdo; Pré-Condição: Ter instalado o app e ter Internet; Pós-Condição: Usuário tem acesso a sua conta
Atores | Usuário que possui conta no aplicativo
Recursos | Internet, aplicativo instalado e conta válida
Exceção | Internet cair, servidor fora do ar, senha inválida, conta inexistente
Episódios | Usuário quer se inscrever no aplicativo para salvar seus dados, abre o aplicativo. Usuário clica no menu que fica no canto superior esquerdo. Usuário clica no botão ‘Entrar na sua conta’. Usuário informa o seu CPF e sua senha. Usuário clica no botão ‘Entrar’. Se o usuário não possuir conta, usuário clica no botão ‘Criar sua conta’. Se o usuário não informou o CPF e/ou senha inválidos, usuário informa o CPF e senha corretos

## Versionamento
Data | Versão | Descrição | Autor 
------ | --------- | ---------- | --------
08/10/2020 | 1.0 | Criação dos cenários | Rafael
08/10/2020 | 1.1 | Revisão | Itallo