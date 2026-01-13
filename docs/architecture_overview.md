# Architecture Overview

Este documento descreve a arquitetura proposta para o projeto de estudo de Engenharia de Dados.

## Visão Geral
O fluxo de dados inicia em fontes transacionais e externas, passa por camadas de ingestão e tratamento, e finaliza em uma camada analítica otimizada para consumo.

## Fontes de Dados
- Sistema OLTP (clientes e assinaturas)
- Arquivos CSV
- APIs externas (Receita Federal e Pagamentos)

## Camadas
- **Bronze**: persistência dos dados crus
- **Silver**: validação, padronização e enriquecimento
- **Gold**: dados modelados para análise

## Benefícios da Arquitetura
- Separação clara de responsabilidades
- Maior controle de qualidade
- Facilidade de evolução e manutenção

