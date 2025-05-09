# Exploração do Índice do Azure AI Search (UI) - Laboratório Microsoft Learning

[![Status](https://img.shields.io/badge/status-concluído-brightgreen)](https://img.shields.io/badge/status-conclu%C3%ADdo-brightgreen)
[![Laboratório](https://img.shields.io/badge/laborat%C3%B3rio-Azure%20AI%20Search-blue)](https://microsoftlearning.github.io/mslearn-ai-fundamentals/Instructions/Labs/11-ai-search.html)

## Descrição do Laboratório

Este repositório documenta minha experiência ao realizar o laboratório "Explore an Azure AI Search index (UI)" do Microsoft Learning. O objetivo principal do laboratório foi entender como interagir e explorar um índice do Azure AI Search utilizando a interface do portal do Azure.

## Objetivos Cumpridos no Laboratório

* Conectar-se a um serviço de Azure AI Search existente através do portal do Azure.
* Explorar a estrutura de um índice, incluindo seus campos e tipos de dados.
* Realizar pesquisas básicas e avançadas utilizando a interface de consulta.
* Aplicar filtros e ordenação aos resultados da pesquisa.
* Analisar os resultados da pesquisa e entender a relevância dos documentos.
* (Inclua outros objetivos específicos que você alcançou no laboratório)

## Processos Técnicos Documentados

### 1. Conexão ao Serviço de Azure AI Search

1.  Navegue até o portal do Azure ([https://portal.azure.com/](https://portal.azure.com/)).
2.  Localize o grupo de recursos onde o serviço de Azure AI Search estava provisionado.
3.  Selecione o serviço de Azure AI Search na lista de recursos.
4.  No painel de visão geral, encontre e clique na opção para acessar o "Search explorer".

### 2. Exploração da Estrutura do Índice


1.  No "Search explorer", selecione o índice que foi fornecido no laboratório (ex: `hotels-sample-index`).
2.  Explore as guias disponíveis: "Overview", "Fields", "Scoring profiles", "Synonym maps", etc.
3.  Observe os nomes dos campos, seus tipos de dados e se são pesquisáveis, filtráveis, ordenáveis ou facetáveis.

### 3. Realização de Pesquisas

1.  Na guia "Search", digite um termo de pesquisa simples (ex: `hotel`).
2.  Analise os resultados exibidos, observando os campos relevantes e o snippet de texto destacado.
3.  Experimente pesquisas mais complexas utilizando operadores booleanos (ex: `hotel AND piscina`).

### 4. Aplicação de Filtros

1.  Na seção de "Filters", selecione um campo (ex: `Category`) e um valor para filtrar (ex: `Luxury`).
2.  Observe como os resultados da pesquisa foram atualizados para corresponder ao filtro aplicado.
3.  Experimente combinar múltiplos filtros.

### 5. Ordenação dos Resultados

1.  Na seção de "Order by", selecione um campo para ordenar (ex: `Rating`) e a direção (ascendente ou descendente).
2.  Verifique se os resultados foram ordenados conforme o critério selecionado.
