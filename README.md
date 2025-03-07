# Retail Data Pipeline

Este projeto implementa um pipeline de dados para análise de **retail orders**. Os dados são extraídos de fontes Kaggle, processados com Pandas, armazenados em um banco de dados SQL Server e analisados por meio de consultas SQL.

## Fluxo do Projeto
1. **Extração de dados**: Dados de retail orders são extraídos de Kaggle.
2. **Processamento**: O Pandas é usado para tratar e transformar os dados.
3. **Armazenamento**: Os dados processados são inseridos em um banco de dados SQL Server.
4. **Análise**: Consultas SQL são usadas para extrair insights dos dados.

## Tecnologias Utilizadas
- Python
- Pandas
- SQL Server
- Kaggle API

## Como Rodar
1. Clone este repositório.
2. Instale as dependências:  
   ```bash
   pip install -r requirements.txt
   ```
3. Configure as credenciais da Kaggle API e o acesso ao banco de dados SQL Server.
4. Execute o script principal para iniciar o pipeline.
