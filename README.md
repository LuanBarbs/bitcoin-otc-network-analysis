# Bitcoin OTC Trust Weighted Signed Network — Análise de Rede
Este projeto faz parte da disciplina Modelagem de Redes Complexas e tem como objetivo analisar a rede de confiança Bitcoin OTC disponível no [Stanford SNAP](https://snap.stanford.edu/data/soc-sign-bitcoin-otc.html).

# Descrição

A análise foi realizada a partir do dataset de transações de confiança entre usuários da plataforma Bitcoin OTC.
Foram exploradas as propriedades estruturais e dinâmicas da rede, incluindo:

- Criação e visualização do grafo;
- Métricas de centralidade e densidade;
- Detecção de comunidades;
- Comparação com modelos teóricos de redes;
- Análise de robustez (falhas e ataques);
- Evolução temporal e centralidade dinâmica.

# Tecnologias utilizadas

- Python
- NetworkX
- Matplotlib / Seaborn
- Pandas / Numpy
- Google Colab

# Estrutura do repositório

```
├── notebooks/
│   └── bitcoin_otc_analysis.ipynb   # Notebook principal
├── data/
│   └── bitcoin-otc.txt              # Instruções para obter o dataset
├── docs/
│   └── Redes Complexas - SNAP.pdf
└── README.md
```

# Fonte dos dados

Dataset: [Bitcoin OTC trust weighted signed network (SNAP)](https://snap.stanford.edu/data/soc-sign-bitcoin-otc.html)

# Autor

Luan Barbosa

Disciplina: Modelagem de Redes Complexas

Instituição: UFJF

Contato: luanhenrique112004@gmail.com

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/10sFTtiWn4KO4bziI4YhLjtKnWLazc4C6?usp=sharing)
