# 2025-One-Billion-Row-Challenge
Teste de um pipeline ETL para processar 1 bilhão de linhas


1. Rodar gerador python
> python criar_dataset_csv.py

2. Instalar duckdb
> curl --fail --location --progress-bar --output duckdb_cli-linux-amd64.zip https://github.com/duckdb/duckdb/releases/download/v1.1.3/duckdb_cli-linux-amd64.zip && unzip duckdb_cli-linux-amd64.zip

3. Instalar dependências
> pip install tqdm
> pip install duckdb