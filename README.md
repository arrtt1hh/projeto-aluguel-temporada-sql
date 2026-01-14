# Projeto Aluguel Temporada SQL

Implementação de banco de dados relacional para gestão de locações, seguindo padrões **Firjan SENAI**.

## 🛠️ Estrutura
- **`scripts/01_estrutura/`**: Scripts DDL (Criação de tabelas).
- **`1_base.sql`**: Definição de Hóspedes, Endereços e Propriedades.

## 🚀 Execução
1. Certifique-se de possuir um servidor **PostgreSQL** ativo.
2. Execute o script `1_base.sql`. O código utiliza `DROP TABLE IF EXISTS` para garantir um ambiente limpo a cada execução.

## 📊 Entidades
- **Endereços**: Chave primária vinculada a propriedades.
- **Hóspedes**: Registro com restrição de e-mail único.
- **Propriedades**: Cadastro de imóveis com validação de capacidade.
