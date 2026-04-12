# Dashboard de Vendas - Streamlit

Dashboard interativo para análise de vendas criado com Streamlit, Pandas e Plotly.

## Como executar

1. Clone o repositório:
```bash
git clone https://github.com/SEU_USERNAME/NOME_DO_REPO.git
cd NOME_DO_REPO
```

2. Crie e ative o ambiente virtual:
```bash
python -m venv avprojstreamlit
avprojstreamlit\Scripts\activate  # Windows
# ou
source avprojstreamlit/bin/activate  # Linux/Mac
```

3. Instale as dependências:
```bash
pip install streamlit pandas plotly requests
```

4. Execute o dashboard:
```bash
streamlit run Dashboard.py
```

## Funcionalidades

- Análise de receita por estados (mapa interativo)
- Receita mensal
- Top estados por receita
- Receita por categoria de produto
- Análise de vendedores (receita e quantidade de vendas)

## Dados

Os dados são obtidos da API: https://labdados.com/produtos