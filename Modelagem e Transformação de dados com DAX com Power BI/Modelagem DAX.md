# Modelagem e Transformação de Dados com DAX no Power BI

## Descrição

Este projeto consiste na modelagem e transformação de dados utilizando DAX no Power BI. A partir da tabela única **"Financial Sample"**, foram criadas tabelas dimensão e fato seguindo o modelo de **esquema em estrela**.

## Estrutura do Modelo

- **Financials_origem** (backup)
- **D_Produtos** – Informações de produtos e métricas agregadas
- **D_Produtos_Detalhes** – Detalhes como preço, unidades vendidas e faixa de desconto
- **D_Descontos** – Dados sobre descontos aplicados
- **D_Detalhes** – Informações complementares sobre vendas
- **D_Calendário** – Criada via DAX (`CALENDAR()`)
- **F_Vendas** – Fato contendo vendas e atributos relevantes

## Etapas do Projeto

1. Extração e separação das tabelas a partir da base original.
2. Aplicação de transformações e agregações com DAX.
3. Criação do calendário dinâmico com `CALENDAR()`.
4. Construção do esquema em estrela.
5. Reorganização e limpeza dos dados.

## Como Usar

1. Abra o arquivo `.pbix` no Power BI.
2. Analise o modelo e as medidas criadas.
3. Explore os dados e relatórios gerados.

