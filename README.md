# 📊 Dashboard de Vendas - Streamlit

Dashboard interativo e moderno para análise completa de dados de vendas, desenvolvido com tecnologias Python de ponta. Visualize insights valiosos sobre performance de vendas, receita e comportamento de clientes através de gráficos dinâmicos e intuitivos.

## ✨ Funcionalidades

- 🗺️ **Mapa Interativo**: Receita por estados brasileiros com visualização geográfica
- 📈 **Análise Temporal**: Receita mensal com tendências e padrões sazonais
- 🏆 **Top Performers**: Ranking de estados e categorias por receita
- 👥 **Análise de Vendedores**: Performance individual (receita e volume de vendas)
- 📱 **Interface Responsiva**: Design adaptável para diferentes dispositivos
- 🔄 **Dados em Tempo Real**: Conexão com API para dados atualizados

## 🛠️ Tecnologias Utilizadas

- **Streamlit**: Framework web para aplicações de dados
- **Pandas**: Manipulação e análise de dados
- **Plotly**: Gráficos interativos e visualizações avançadas
- **Python**: Linguagem de programação principal

## 📊 Métricas Disponíveis

- Receita total e por período
- Distribuição geográfica de vendas
- Performance por categoria de produto
- Análise comparativa de vendedores
- Tendências mensais e sazonais

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

## Dados

Os dados são obtidos da API: https://labdados.com/produtos