# 🧃 Projeto Banco de Dados - Sucos Vendas

Este repositório contém o script de criação e inserção de dados para o banco de dados **sucos_vendas**, desenvolvido utilizando o **Microsoft SQL Server (SSMS)**. 

O projeto simula o sistema de cadastro de uma empresa de bebidas, gerenciando as informações de clientes e o catálogo de produtos disponíveis.

## 🛠️ Tecnologias Utilizadas
* **SGBD:** Microsoft SQL Server
* **Ferramenta:** SQL Server Management Studio (SSMS)
* **Linguagem:** T-SQL (Transact-SQL)

## 📊 Estrutura do Banco de Dados
O projeto é composto por duas tabelas principais com relacionamentos e restrições (Chaves Primárias):

1. **tabela de clientes:** Armazena dados cadastrais dos clientes, incluindo CPF (Primary Key), endereço, data de nascimento, idade, sexo, limite de crédito, volume de compra e se já realizou a primeira compra.
2. **tabela de produtos:** Armazena o catálogo de sucos da empresa com código do produto (Primary Key), nome, tipo de embalagem, tamanho, sabor e preço de lista.

## 🚀 Como Executar o Projeto
1. Faça o download ou copie o arquivo `.sql` presente neste repositório.
2. Abra o **SQL Server Management Studio (SSMS)**.
3. Conecte-se à sua instância local.
4. Abra o arquivo de script no SSMS e clique em **Executar (F5)** para criar o banco de dados, as tabelas e popular os registros automaticamente.
