## Tática Total EC - Simulador de Gestão de Clubes de Futebol
Um projeto de analise de dados de clubes de futebol. Este projeto utiliza Python e SQLite para gerenciar os dados e Faker para gerar informações fictícias.

## Funcionalidades
- Criação de tabelas no banco de dados SQLite para armazenar informações de usuários, jogadores, times, ligas e estádios.
- Geração automática de dados fictícios para jogadores, times e estádios.
- Associação de jogadores a times e times a ligas.

## Tecnologias Utilizadas
- Python
- SQLite
- Faker (para geração de dados fictícios)

## Como Executar
1. Certifique-se de ter o Python instalado em sua máquina.
2. Instale as dependências necessárias executando:
   ```bash
   pip install -r requirements.txt
   ```
3. Execute os notebooks na seguinte ordem:
   - `database.ipynb`: Para criar as tabelas e popular o banco de dados com dados fictícios.
   - `analise.ipynb`: Para realizar análises e visualizações baseadas nos dados gerados.

## Estrutura do Projeto
- `database.ipynb`: Contém o código para criação e preenchimento do banco de dados.
- `analise.ipynb`: Contém o código para análise e visualização dos dados.
- `README.md`: Este arquivo, com informações sobre o projeto.

## Contribuição
Contribuições são bem-vindas! Sinta-se à vontade para abrir issues e enviar pull requests.