# Hypersena

Simulador estatístico de alto desempenho, baseado em métodos de
Monte Carlo e distribuições hipergeométricas, para análise de
probabilidades em loterias e de retorno sobre o investimento (ROI)
financeiro, utilizando a biblioteca NumPy.

## Funcionalidades

- Simulação de sorteios de loterias.
- Análise estatística de probabilidades.
- Simulações de Monte Carlo.
- Cálculo de custos, premiações e retorno sobre o investimento (ROI).
- Persistência e gerenciamento de dados históricos.
- Interface web interativa com Streamlit.
- Testes automatizados com pytest.

## Tecnologias

- Python
- NumPy
- Pandas
- Streamlit
- Pytest
- Docker

## Estrutura do projeto

```text
hypersena/
├── data/
│   └── .gitkeep
├── src/
│   ├── __init__.py
│   ├── engine.py
│   ├── finance.py
│   ├── data_manager.py
│   └── .gitkeep
├── tests/
│   ├── __init__.py
│   ├── test_engine.py
│   ├── test_finance.py
│   └── .gitkeep
├── app.py
├── requirements.txt
├── Dockerfile
├── .gitignore
└── README.md