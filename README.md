# Preparação de Dados para Modelagem

Este repositório contém um script em Python desenvolvido na aula de Data Preparation da DNC para a preparação de dados, visando a modelagem de projetos. O script é executado no Google Colab e abrange a limpeza, transformação e integração de diferentes conjuntos de dados.

Para começar, foi feito o upload dos arquivos CSV (DataPrepFinal.csv, campaign.csv, invested.csv) quando solicitado.

A preparação dos dados segue várias etapas. Primeiro, os dados são carregados para o ambiente do Colab. Em seguida, realiza-se a limpeza dos dados, removendo colunas irrelevantes, ajustando tipos de dados e tratando valores ausentes. Depois, novos atributos são criados para enriquecer o conjunto de dados, como a duração do projeto (time_range).

Na etapa de mesclagem, integramos os diferentes conjuntos de dados (campaign.csv e invested.csv) ao DataFrame principal, unindo as informações de campanhas e apoiadores aos dados dos projetos. Finalmente, são feitas transformações adicionais e ajustes finais para garantir que os dados estejam prontos para a modelagem, removendo colunas intermediárias e garantindo a consistência dos tipos de dados.

Este projeto é essencial para a criação de um conjunto de dados limpo e estruturado, pronto para ser usado em análises e modelagem preditiva.
