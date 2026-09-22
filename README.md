# Predição de Vendas de Produtos Perecíveis Utilizando Séries Temporais Correlacionadas

Trabalho de Conclusão de Curso — MBA em Ciência de Dados (UNIFOR)
Autor: Rodrigo Amadeu Reis Cavalcante

## Sobre este repositório

Este repositório reúne o material de apoio ao artigo/TCC que investiga se a previsão diária das
vendas de BANANA em um supermercado pode ser aprimorada ao combinar o histórico do próprio
produto com a série temporal de outro produto correlacionado.

## Conteúdo

- `analise_banana.ipynb`: notebook Jupyter único e reprodutível com toda a análise exploratória,
  o tratamento dos dados, a análise de correlação e os modelos de previsão descritos no trabalho.
- `amostra_serie_mercadorias.csv`: amostra representativa (estratificada por dia, cobrindo os 90
  dias do período analisado) da base transacional de vendas utilizada no estudo. A base completa
  não é disponibilizada publicamente por motivos de confidencialidade comercial; esta amostra
  serve para verificação da estrutura de dados descrita na Seção 3.1 do trabalho.

## Estrutura dos dados

| Coluna | Descrição |
|---|---|
| `sale_id` | Identificador da transação de venda (ticket) |
| `date_time` | Data e hora da transação |
| `store_id` | Identificador da loja |
| `unit_value` | Valor unitário do produto |
| `amount` | Quantidade comercializada |
| `description` | Descrição comercial do produto |
| `product_id` | Identificador único do produto |
