# Análise de Vendas com SQL e Python

Este projeto tem como objetivo realizar análises em uma base de dados de vendas utilizando SQL e Python. A base de dados contém informações sobre compras, clientes, produtos, valores unitários e quantidades vendidas. As análises são realizadas por meio de consultas SQL em um banco de dados SQLite, carregado a partir de um arquivo CSV.

## Tabela de Conteúdos
1. [Estrutura do Projeto](#estrutura-do-projeto)
2. [Como Executar](#como-executar)
3. [Consultas Realizadas](#consultas-realizadas)
4. [Tecnologias Utilizadas](#tecnologias-utilizadas)
5. [Contribuição](#contribuição)

---

## Estrutura do Projeto

O projeto consiste em:
- Um arquivo CSV (`TB_VENDAS_TAREFA.csv`) contendo os dados de vendas.
- Um script Python que carrega os dados no SQLite e executa consultas SQL.
- Consultas SQL para análise dos dados.

## Como Executar

1. **Pré-requisitos**:
   - Python 3.x instalado.
   - Bibliotecas necessárias: `pandas` e `sqlite3`.

2. **Instalação das dependências**:
   ```bash
   pip install pandas
