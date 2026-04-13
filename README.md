# 📊 Dashboard de Vendas - Streamlit

Dashboard interativo e completo para análise de dados de vendas, desenvolvido com tecnologias Python modernas. Criado a partir do curso 'Streamlit: construindo um dashboard interativo' oferecido pela Alura.

## ✨ Funcionalidades Principais

### 🏠 **Página Principal (Dashboard.py)**
- **Filtros Avançados**: Filtragem por região, ano e vendedores específicos
- **Interface com Abas**:
  - 📈 **Receita**: Análise de receita com mapas geográficos, gráficos mensais e ranking por categoria
  - 📊 **Quantidade de Vendas**: Visualização de volume de vendas por estado, período e categoria
  - 👥 **Vendedores**: Performance individual com ranking de receita e volume

### 📄 **Página Dados Brutos**
- **Filtros Granulares**: Seleção por produto, preço, data, frete, vendedor, local, avaliação, pagamento e parcelas
- **Seleção de Colunas**: Personalização das colunas exibidas na tabela
- **Download de Dados**: Exportação dos dados filtrados em formato CSV
- **Visualização Completa**: Tabela interativa com contagem de linhas e colunas

## 🛠️ Tecnologias Utilizadas

- **Streamlit**: Framework web para aplicações de dados interativas
- **Pandas**: Manipulação e análise de dados
- **Plotly**: Gráficos interativos e visualizações avançadas
- **Requests**: Conexão com API externa para dados
- **Python**: Linguagem de programação principal

## 📊 Métricas e Visualizações

### Mapas Geográficos
- Receita por estados brasileiros
- Volume de vendas por localização
- Visualização interativa com Plotly

### Gráficos Temporais
- Receita mensal com tendências
- Volume de vendas ao longo do tempo
- Análise sazonal e anual

### Rankings e Comparativos
- Top estados por receita/vendas
- Top categorias de produtos
- Performance de vendedores
- Comparativos interativos

### Tabelas Interativas
- Dados brutos com filtros avançados
- Seleção personalizada de colunas
- Download em CSV
- Contagem automática de registros

## 🔧 Funcionalidades Técnicas

- **Cache Inteligente**: Uso de `@st.cache_data` para otimização de performance
- **API Integration**: Conexão em tempo real com API de dados
- **Filtros Dinâmicos**: Interface responsiva com múltiplas opções de filtragem
- **Exportação de Dados**: Download de datasets filtrados
- **Layout Responsivo**: Design adaptável para diferentes dispositivos

## 📁 Estrutura do Projeto

```
proj_streamlit/
├── Dashboard.py              # Página principal com dashboard interativo
├── README.md                 # Documentação do projeto
├── LICENSE                   # Licença MIT
├── .gitignore               # Arquivos ignorados pelo Git
├── .streamlit/              # Configurações do Streamlit
│   └── config.toml
├── pages/                   # Páginas adicionais
│   └── Dados brutos.py     # Página de dados brutos com filtros
└── avprojstreamlit/         # Ambiente virtual (ignorado pelo Git)
    └── ...
```

## 🚀 Como Usar

### Pré-requisitos
- Python 3.8 ou superior
- Git (opcional, para clonar o repositório)

### Instalação e Execução

1. **Clone o repositório** (ou baixe os arquivos):
```bash
git clone https://github.com/LLenha/proj_streamlit_alura.git
cd proj_streamlit_alura
```

2. **Crie o ambiente virtual**:
```bash
python -m venv avprojstreamlit
```

3. **Ative o ambiente virtual**:
```bash
# Windows
avprojstreamlit\Scripts\activate

# Linux/Mac
source avprojstreamlit/bin/activate
```

4. **Instale as dependências**:
```bash
pip install streamlit pandas plotly requests
```

5. **Execute o dashboard**:
```bash
streamlit run Dashboard.py
```

6. **Acesse no navegador**:
   - O Streamlit abrirá automaticamente em `http://localhost:8501`
   - Use o menu lateral para navegar entre as páginas

## 🎯 Navegação

### Página Principal (Dashboard.py)
- **Filtros Laterais**: Região, ano, vendedores
- **Abas**:
  - **Receita**: Mapas e gráficos de receita
  - **Quantidade de Vendas**: Análise de volume
  - **Vendedores**: Performance individual

### Página Dados Brutos
- **Filtros Expansíveis**: Múltiplas opções de filtragem
- **Seleção de Colunas**: Personalize a visualização
- **Download**: Exporte dados filtrados em CSV

## 🤝 Contribuição

Este projeto foi desenvolvido como parte de um curso de aprendizado. Sugestões e melhorias são bem-vindas!

Para contribuir:
1. Faça um fork do projeto
2. Crie uma branch para sua feature (`git checkout -b feature/AmazingFeature`)
3. Commit suas mudanças (`git commit -m 'Add some AmazingFeature'`)
4. Push para a branch (`git push origin feature/AmazingFeature`)
5. Abra um Pull Request

## 📝 Licença

Este projeto está sob a licença MIT. Veja o arquivo [LICENSE](LICENSE) para mais detalhes.

## 👨‍💻 Autor

**LLenha** - Desenvolvimento inicial como projeto de aprendizado

---

⭐ **Dê uma estrela se este projeto te ajudou!**
```bash
streamlit run Dashboard.py
```

## Dados

Os dados são obtidos da API: https://labdados.com/produtos