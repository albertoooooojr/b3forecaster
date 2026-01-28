
# 📈 B3 Stock Forecast & RSI Scanner

![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=for-the-badge&logo=streamlit&logoColor=white )
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white )
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white )
![yfinance](https://img.shields.io/badge/yfinance-000000?style=for-the-badge&logo=yahoo&logoColor=white )
![Prophet](https://img.shields.io/badge/Prophet-0072B2?style=for-the-badge&logo=facebook&logoColor=white )

Uma aplicação web interativa construída com Streamlit para analisar e prever o comportamento de ações da bolsa de valores brasileira (B3).

A ferramenta oferece duas funcionalidades principais:
1.  **RSI Scanner:** Identifica rapidamente ações que estão em níveis de sobrecompra (RSI > 70) ou sobrevenda (RSI < 30).
2.  **Análise e Previsão Detalhada:** Permite ao usuário escolher uma ação específica para visualizar seu histórico de preços, gráfico de RSI e uma previsão de preços futuros usando o modelo Prophet do Facebook.

---

## 🚀 Funcionalidades

*   **Scanner de IFR (RSI):** Varre uma lista das principais ações da B3 e exibe uma tabela com aquelas que estão atualmente sobrecompradas ou sobrevendidas, ajudando a identificar potenciais pontos de entrada ou saída.
*   **Seleção de Ações:** Um menu dropdown permite escolher facilmente qualquer ação da lista para uma análise aprofundada.
*   **Visualização de Dados Históricos:** Exibe o gráfico com o preço de fechamento histórico da ação selecionada desde 2020.
*   **Gráfico de RSI:** Plota o Índice de Força Relativa (RSI) ao longo do tempo, com marcações claras para os níveis de 70 (sobrecompra) and 30 (sobrevenda).
*   **Previsão de Preços Futuros:** Utiliza o modelo `Prophet` para gerar uma previsão de preços para os próximos dias (o usuário pode escolher de 7 a 90 dias).
*   **Análise de Componentes da Previsão:** Mostra os componentes da previsão, como tendência e sazonalidade diária, para um entendimento mais profundo do modelo.

---

## 🛠️ Tecnologias Utilizadas

*   **[Streamlit](https://streamlit.io/ ):** Para a criação da interface web interativa.
*   **[yfinance](https://pypi.org/project/yfinance/ ):** Para baixar os dados históricos de cotações das ações diretamente do Yahoo Finance.
*   **[Pandas](https://pandas.pydata.org/ ):** Para manipulação e análise dos dados.
*   **[Prophet](https://facebook.github.io/prophet/ ):** Para a modelagem e previsão de séries temporais.
*   **[Matplotlib](https://matplotlib.org/ ):** Para a criação dos gráficos de RSI e dos componentes da previsão.

---

## ⚙️ Instalação e Execução

Siga os passos abaixo para rodar o projeto em sua máquina local.

**1. Clone o repositório:**
```bash
git clone https://github.com/albertoooooojr/b3-forecast-app.git
cd b3-forecast-app

**2. Crie um ambiente virtual (recomendado ):**
```bash
python -m venv venv
source venv/bin/activate  # No Windows: venv\Scripts\activate
```

**3. Instale as dependências:**
Crie um arquivo `requirements.txt` com o seguinte conteúdo:
```txt
streamlit
pandas
yfinance
prophet
matplotlib
```
E então instale as bibliotecas com o comando:
```bash
pip install -r requirements.txt
```

**4. Execute a aplicação:**
Com o ambiente virtual ativado, rode o seguinte comando no terminal:
```bash
streamlit run seu_arquivo.py
```
> *Troque `seu_arquivo.py` pelo nome que você deu ao seu script Python.*

A aplicação será aberta automaticamente no seu navegador!

---

## 🖼️ Preview da Aplicação

*(Você pode adicionar screenshots da sua aplicação aqui para deixar o README mais visual)*

**Scanner RSI:**
![Scanner RSI](https://i.imgur.com/link-para-sua-imagem.png )

**Gráfico de Previsão:**
![Gráfico de Previsão](https://i.imgur.com/link-para-outra-imagem.png )

