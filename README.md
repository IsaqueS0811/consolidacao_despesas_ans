# TESTE DE INTEGRAÇÃO COM API PÚBLICA
# Sobre o projeto
Este projeto foi desenvolvido como parte do Teste Técnico para Estágio.
O objetivo é consolidar os dados de despesas relacionadas a Eventos/Sinistros a partir das demonstrações contábeis trimestrais disponibilizadas pela ANS.

O codigo realiza a extração automática de arquivos ZIP (quando presentes),
processa os arquivos CSV e gera um arquivo consolidado contendo as informações
padronizadas dos últimos três trimestres.

# Objetivo
- Processar dados contábeis trimestrais da ANS
- Identificar e filtrar despesas relacionadas a Eventos/Sinistros
- Consolidar os dados em um único arquivo CSV
- Garantir organização, clareza e reprodutibilidade do processo

# Estrutura do projeto

IntuitiveCare/
│
├── data/
│ ├── 1T2025.csv
│ ├── 2T2025.csv
│ ├── 3T2025.csv
│ └── consolidado_despesas.csv
│
├── etapa1.py
└── README.md

# Tecnologias utilizadas
- Python 3.13
- Pandas
- Pathlib
- Zipfile

# Pré-requisitos
Antes de executar o projeto, é necessário ter instalado na máquina:
- Python 3.9 ou superior

## Como executar o projeto

1. Clone o repositório ou extraia os arquivos
2. Coloque os arquivos ZIP ou CSV na pasta `data/`
3. Execute o script:

```bash
python etapa1.py

