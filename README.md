# projeto-sql-ecommerce.
# Engenharia e Análise de Dados: E-commerce Internacional (Python & SQL)

Este projeto prático demonstra um fluxo ponta a ponta de dados (End-to-End). Utiliza Python para a engenharia e simulação de dados em massa e PostgreSQL para a modelagem relacional e extração de métricas estratégicas de negócios.

## 🛠️ Tecnologias e Ferramentas Utilizadas
* **Python**: Geração automatizada de dados em massa com a biblioteca `Faker` e estruturação com `Pandas`.
* **PostgreSQL**: Sistema de Gerenciamento de Banco de Dados Relacional (SGBD) para armazenamento.
* **pgAdmin 4**: Interface e ambiente de desenvolvimento para execução dos scripts SQL.
* **SQL Avançado**: Aplicação prática de `INNER JOIN`, funções de agregação (`SUM`), agrupamentos (`GROUP BY`), filtros (`WHERE`) e ordenação analítica (`ORDER BY`).

## 📁 Estrutura de Arquivos no Repositório
* `gerar_dados.py`: Script Python responsável por criar os dados fictícios internacionais.
* `usuario_faker.csv`: Massa de dados contendo o cadastro de 100 clientes de múltiplos países (incluindo Portugal, Alemanha e Liechtenstein).
* `pedidos_faker.csv`: Massa de dados contendo o histórico de 500 transações financeiras.
* `script_banco.sql`: Script SQL contendo a criação das tabelas e as consultas analíticas.

## 📊 Regra de Negócio Analisada
O relatório consolida o faturamento total acumulado apenas de clientes cujas compras foram finalizadas e despachadas com sucesso (status 'Entregue'). Isso permite que a gestão identifique instantaneamente os clientes de maior valor dentro de cada mercado europeu.

## 📈 Resultado da Consulta Analítica
O banco de dados processou as consultas com sucesso e retornou os dados consolidados exibidos na imagem abaixo:

![Resultados do Banco](resultado.png)
