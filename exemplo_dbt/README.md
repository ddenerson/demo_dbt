# 📦 Projeto de exemplo dbt

_Este projeto foi adaptado para servir como referência em português._

Bem-vindo! Aqui você encontra um projeto demonstrativo do dbt que pode ser utilizado para estudar e experimentar a ferramenta.

## Passos para começar

1. Configure sua conexão de banco de dados no arquivo `~/.dbt/profiles.yml` com o profile `exemplo_dbt`.
2. No diretório do projeto, execute `dbt deps` para instalar os pacotes necessários.
3. Execute `dbt build` para rodar seeds, modelos e testes.

## Estrutura principal

- `models/`: modelos organizados em camadas de _staging_, _intermediate_ e _marts_.
- `macros/`: macros auxiliares utilizadas pelo projeto.
- `seeds/`: arquivos de carga inicial de dados (quando existirem).

Ajuste livremente as configurações para adequá-las ao seu ambiente.
