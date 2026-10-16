# Trabalho MQ — Ames Housing

Avaliações práticas (AP1, AP2 e AP3) da disciplina Métodos Quantitativos em Computação — Unifor, 2026.2. Prof. Me. Ricardo Carubbi.

## Integrantes

- Nome Completo — matrícula
- Nome Completo — matrícula

## Estrutura

```text
README.md            este arquivo
requirements.txt     dependências Python
.gitignore
data/
  raw/               arquivo bruto fornecido pelo professor (não alterado)
  processed/         base pré-processada gerada pela AP1
enunciados/            cópia dos enunciados, rubricas e modelos (github.com/carubbi/MQ/trabalhos)
notebooks/
  ap1.ipynb          AP1 — Análise exploratória do preço de venda
  ap2.ipynb          AP2 — Auditoria de modelos probabilísticos
```

## Preparação do ambiente

```bash
python -m venv .venv
source .venv/bin/activate        # Windows: .venv\Scripts\activate
pip install -r requirements.txt
```

## Execução

Os notebooks devem ser executados em ordem, do início ao fim (reiniciar o kernel e executar todas as células):

1. `notebooks/ap1.ipynb` lê `data/raw/AmesHousing.csv` e gera `data/processed/AmesHousing.csv`.
2. `notebooks/ap2.ipynb` lê `data/processed/AmesHousing.csv`.

Os caminhos são relativos à raiz do repositório; os notebooks funcionam tanto abertos a partir da raiz quanto a partir de `notebooks/`.
