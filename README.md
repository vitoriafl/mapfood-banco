# MapFood Banco de Dados

Repositório responsável pela modelagem e scripts do banco de dados relacional do projeto MapFood.

## 🗄️ Estrutura

- `mysqlmapfoodscript.sql`: Script SQL principal para criação das tabelas e relacionamentos no MySQL.
- `.brM3`: Arquivos de modelagem do BrModelo (v2, v3, v4).
- `.mwb`: Diagrama do MySQL Workbench.
- `mapfoodv4_imagem.pdf`: Visualização do diagrama de entidades e relacionamentos (DER).

## 📊 Entidades Principais

- **Comerciante & Loja**: Gestão dos estabelecimentos.
- **Consumidor**: Usuários finais da plataforma.
- **Evento**: Feiras e eventos onde as lojas participam.
- **Localização**: Endereços físicos e horários de funcionamento.
- **Avaliações & Denúncias**: Sistema de feedback e moderação.

## 🚀 Como Utilizar

1.  Tenha um servidor **MySQL** (versão 8.0+) em execução.
2.  Crie o banco de dados:
    ```sql
    CREATE DATABASE mapfood;
    USE mapfood;
    ```
3.  Execute o script `mysqlmapfoodscript.sql` para gerar a estrutura.
