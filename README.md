# Métodos Quantitativos — AP integrada (Ames Housing)

Repositório das avaliações práticas (AP1, AP2, AP3) da disciplina Métodos
Quantitativos em Computação (T199), baseadas na base Ames Housing.

- **Integrantes:** Adriel Medeiros Lins
- **Turma:** T199-64
- **Característica qualitativa $B$ atribuída:** TODO

## Estrutura do repositório

```text
README.md
requirements.txt
.gitignore
data/
  raw/         dados brutos fornecidos pelo professor (não alterados)
  processed/   dados organizados, gerados de forma reproduzível pelo notebook
notebooks/
  ap1.ipynb    AP1 — análise exploratória
  ap2.ipynb    AP2 — auditoria de modelo probabilístico (a partir da Unidade II)
  ap3.ipynb    AP3 — modelagem por regressão (a partir da Unidade III)
```

## Preparação do ambiente

```bash
python3 -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
```

## Execução

1. Colocar o arquivo bruto fornecido pelo professor em `data/raw/AmesHousing.txt`
   e preservá-lo sem alterações (o arquivo é versionado no repositório).
2. Abrir `notebooks/ap1.ipynb` e executar todas as células, do início ao fim,
   em um kernel reiniciado (sem depender de estado externo).
3. O notebook gera `data/processed/AmesHousing.csv` de forma reproduzível ao
   final da execução.

## Declaração de uso de inteligência artificial

Ver seção correspondente em cada notebook (`notebooks/ap1.ipynb`, etc.).
