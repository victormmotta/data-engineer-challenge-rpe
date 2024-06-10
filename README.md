# Data Engineer Challenge

## Descrição

Este repositório contém a solução para o desafio técnico de Engenheiro de Dados. O objetivo é desenvolver um pipeline de dados utilizando Databricks, seguindo o modelo de medalhão.

## Notebooks

- `bronze_layer.dbc`: Carregamento dos dados brutos.
- `silver_layer.dbc`: Processamento e limpeza dos dados.
- `gold_layer.dbc`: Criação da visão analítica.
- `full_load.dbc`: Executa todo o pipeline para cargas full.
- `incremental_load.dbc`: Executa o pipeline para cargas incrementais.

## Instruções de Configuração

1. Clone o repositório:
   ```bash
   git clone https://github.com/seu-usuario/data-engineer-challenge.git

2. Importe os notebooks no Databricks:
- Navegue até o workspace do Databricks.
- Clique em Workspace > Users > Seu Usuário.
- Clique com o botão direito na pasta do seu usuário e selecione Import.
- Faça o upload dos notebooks baixados (.ipynb ou .dbc).

## Execução

1. Carga Full:
- Navegue até o notebook full_load.ipynb no Databricks.
- Execute todas as células do notebook para realizar uma carga completa dos dados.

2. Cargas Incrementais:
- Navegue até o notebook incremental_load.ipynb no Databricks.
- Execute todas as células do notebook para processar e carregar dados incrementais.

## Dependências

- Databricks
- Cluster configurado no Databricks

## Contato
Para dúvidas, entre em contato pelo e-mail: victor.mmotta@gmail.com



### Passos para Submissão

1. **Baixe os notebooks do Databricks.**
2. **Crie um novo repositório no GitHub.**
3. **Faça upload dos notebooks e do arquivo `README.md` para o repositório.**
4. **[Link do repositório](https://github.com/victormmotta/data-engineer-challenge-rpe)**.

Se precisar de mais assistência ou ajustes, estou aqui para ajudar!
