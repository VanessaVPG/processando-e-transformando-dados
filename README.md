# Relatório do Projeto de Processamento de Dados com Power BI

Este relatório descreve as etapas que realizei no desafio de projeto de Processamento de Dados Simplificado com o Power BI. 

## Criação da Instância no Azure

Para criar a instância no Azure, segui os seguintes passos:
- Criei uma instância no Azure para o banco de dados MySQL.
- Anotei as informações de conexão, incluindo a URL, nome de usuário e senha.

## Criação do Banco de Dados

Com base nos dados disponíveis [no GitHub](https://github.com/julianazanelatto/power_bi_analyst), criei o banco de dados no MySQL no Azure. Carreguei os dados com sucesso para as tabelas "employee," "departament," "dept_locations," "project," "works_on," e "dependent."

## Integração do Power BI com MySQL no Azure

Configurei o Power BI para se conectar ao banco de dados MySQL no Azure. Usei as informações de conexão fornecidas durante a criação da instância.

## Verificação de Problemas na Base de Dados

- Verifiquei os cabeçalhos e tipos de dados nas tabelas do banco de dados.
- Analisei a existência de valores nulos e decidi manter ou remover com base nos requisitos do projeto.
- Identifiquei colaboradores sem gerentes e departamentos sem gerentes.

## Transformação de Dados

Realizei as seguintes transformações de dados:
- Modifiquei os tipos de dados conforme necessário.
- Tratei valores nulos de acordo com os requisitos.
- Preenchi departamentos sem gerentes.

## Mescla de Dados

Mesclei as consultas entre as tabelas "employee" e "departament" para criar uma tabela que associa os colaboradores aos departamentos. Eliminei colunas desnecessárias durante o processo de mescla.

## Consolidação de Dados

- Mesclei as colunas de nome e sobrenome para criar uma única coluna para os nomes dos colaboradores.
- Mesclei os nomes de departamentos e localizações para criar uma única combinação única.
