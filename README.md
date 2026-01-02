# 📊 Dashboard Interativo de Vendas

## 🎯 Objetivo

Dashboard web interativo para análise em tempo real de métricas de vendas, permitindo filtros dinâmicos e visualizações interativas.

## 🚀 Tecnologias Utilizadas

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=for-the-badge&logo=streamlit&logoColor=white)
![Plotly](https://img.shields.io/badge/Plotly-3F4F75?style=for-the-badge&logo=plotly&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)

## ✨ Funcionalidades

### 📈 Visualizações Interativas
- Gráficos de linha para tendências temporais
- Gráficos de barras para comparações
- Mapas de calor para análise de padrões
- Gráficos de pizza para distribuições
- Métricas em cards (KPIs)

### 🔍 Filtros Dinâmicos
- Filtro por período (data início e fim)
- Filtro por região
- Filtro por categoria de produto
- Filtro por faixa de valor

### 📊 Métricas Principais
- Receita Total
- Número de Vendas
- Ticket Médio
- Clientes Únicos
- Taxa de Crescimento

## 📁 Estrutura do Projeto

```
dashboard-vendas/
# 📊 Dashboard Interativo de Vendas

## 🎯 Objetivo

Dashboard web interativo para análise em tempo real de métricas de vendas, permitindo filtros dinâmicos e visualizações interativas.

## 🚀 Tecnologias Utilizadas

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=for-the-badge&logo=streamlit&logoColor=white)
![Plotly](https://img.shields.io/badge/Plotly-3F4F75?style=for-the-badge&logo=plotly&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)

## ✨ Funcionalidades

### 📈 Visualizações Interativas
- Gráficos de linha para tendências temporais
- Gráficos de barras para comparações
- Mapas de calor para análise de padrões
- Gráficos de pizza para distribuições
- Métricas em cards (KPIs)

### 🔍 Filtros Dinâmicos
- Filtro por período (data início e fim)
- Filtro por região
- Filtro por categoria de produto
- Filtro por faixa de valor

### 📊 Métricas Principais
- Receita Total
- Número de Vendas
- Ticket Médio
- Clientes Únicos
- Taxa de Crescimento

## 📁 Estrutura do Projeto

```
dashboard-vendas/
├── app.py
├── data/
│   └── vendas.csv
├── screenshots/
│   └── (adicione imagens aqui para o README)
├── requirements.txt
└── README.md
```

## 🚀 Como Executar

## 📌 Deploy e Dados

- App pública (Streamlit): vá em sua conta no Streamlit Cloud para ver o URL atual do deploy.
- Para usar seus próprios dados, coloque um arquivo CSV em `data/vendas.csv` com as colunas mínimas:
  - `data_venda` (formato ISO, e.g. 2024-01-05)
  - `id_produto`
  - `categoria`
  - `quantidade`
  - `preco_unitario`
  - `regiao`
  - `id_cliente`

O `app.py` irá carregar automaticamente `data/vendas.csv` se o arquivo existir; caso contrário, usará dados de exemplo gerados aleatoriamente.

Para rodar localmente:

```powershell
python -m venv .venv
.\\.venv\\Scripts\\activate
pip install -r requirements.txt
streamlit run app.py
```

### Pré-requisitos
```
Python 3.8+
```

### Instalação

1. Clone o repositório:
```bash
git clone https://github.com/198517/dashboard-vendas.git
cd dashboard-vendas
```

2. Instale as dependências:
```bash
pip install -r requirements.txt
```

3. Execute o dashboard:
```bash
streamlit run app.py
```

4. Acesse no navegador:

```
http://localhost:8501
```

## 📦 Dependências

```
streamlit>=1.28.0
pandas>=2.0.0
plotly>=5.17.0
numpy>=1.24.0
```

## 📸 Screenshots

> Se as imagens não aparecerem abaixo, coloque arquivos PNG/JPG na pasta `screenshots/` com os nomes indicados.

### Dashboard Principal

![Dashboard Principal](screenshots/dashboard_main.png)

### Análise por Região

![Análise Regional](screenshots/dashboard_region.png)

### Tendências Temporais

![Tendências Temporais](screenshots/dashboard_trends.png)

---

## 🎓 Aprendizados

Este projeto demonstra:
- ✅ Desenvolvimento de aplicações web com Streamlit
- ✅ Visualizações interativas com Plotly
- ✅ Design de dashboards profissionais
- ✅ Manipulação de dados em tempo real
- ✅ UX/UI para análise de dados
- ✅ Deploy de aplicações de dados

## 🌟 Destaques Técnicos

- **Performance**: Cache de dados para carregamento rápido
- **Responsividade**: Layout adaptável para diferentes telas
- **Interatividade**: Filtros em tempo real
- **Visualizações**: Gráficos profissionais e interativos
- **Métricas**: KPIs calculados dinamicamente

## 📝 Próximos Passos

- [ ] Adicionar exportação de relatórios em PDF
- [ ] Implementar autenticação de usuários
- [ ] Adicionar previsões com Machine Learning
- [ ] Integrar com banco de dados em tempo real
- [ ] Melhorar screenshots com imagens atualizadas

## 🚀 Deploy

### Streamlit Cloud
```bash
# Faça push para GitHub
git push origin main

# Configure no Streamlit Cloud
# https://streamlit.io/cloud
```

## 👤 Autor

**Anderson de Lima**
- LinkedIn: [anderson-de-lima-analista-de-dados](https://www.linkedin.com/in/anderson-de-lima-analista-de-dados/)
- GitHub: [@198517](https://github.com/198517)

## 📄 Licença

Este projeto está sob a licença MIT.

---

⭐ Se este projeto foi útil para você, considere dar uma estrela!
