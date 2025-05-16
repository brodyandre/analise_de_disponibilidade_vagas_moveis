
# Análise de disponibilidade de vagas de imóveis 📊

> Projeto desenvolvido por [brodyandre](https://github.com/brodyandre)  
> Análise e visualização interativa dos dados de vagas de imóveis disponíveis com foco em qualidade dos dados e insights sobre vagas disponíveis ao longo do tempo.

---

## 🚀 Tecnologias Utilizadas

- Python 3.x  
- [Pandas](https://pandas.pydata.org/) para manipulação de dados  
- [NumPy](https://numpy.org/) para operações numéricas  
- [Plotly](https://plotly.com/python/) para gráficos interativos e elegantes  
- JSON para importação dos dados  

---

## 🎯 Objetivo do Projeto

Este projeto tem como propósito realizar uma análise detalhada dos dados de móveis disponíveis, efetuando o tratamento e a limpeza necessárias para garantir a qualidade do DataFrame. A partir disso, é possível gerar visualizações interativas que facilitam a compreensão e a tomada de decisão baseada em dados, focando na quantidade de vagas disponíveis mensalmente.

---

## 🗂 Estrutura dos Dados

O conjunto de dados original está em formato JSON, contendo informações como:  

- `preco`: preço do móvel (string com valores monetários)  
- `data`: data associada ao registro  
- `vaga_disponivel`: quantidade de vagas disponíveis  

Após o carregamento, os dados passam por processos de limpeza, incluindo:  
- preenchimento de valores nulos  
- conversão de tipos (datas e valores monetários)  
- normalização para formato numérico adequado para análise  

---

## 📊 Descrição da Análise

1. **Importação dos dados**: leitura do arquivo JSON e conversão para DataFrame.  
2. **Tratamento de dados**: limpeza de campos `preco` e `data`, preenchimento de valores ausentes.  
3. **Agregação mensal**: sumarização das vagas disponíveis agrupadas por mês.  
4. **Visualização interativa**: criação de gráfico de barras usando Plotly, com paleta de cores degradê (`Viridis`) e tema escuro para melhor experiência visual.

---

## ⚙️ Como executar

1. Clone o repositório:  
   ```bash
   git clone https://github.com/brodyandre/analise_moveis_disponiveis.git
   cd analise_moveis_disponiveis
   ```

2. Abra o notebook no Google Colab ou em sua IDE preferida que suporte Jupyter notebooks.

3. Instale as dependências necessárias:  
   ```bash
   !pip install pandas numpy plotly
   ```

4. Execute as células para carregar, limpar e visualizar os dados.

---

## 📈 Resultado Esperado

Ao final, você terá um gráfico de barras interativo que permite explorar a disponibilidade de vagas ao longo dos meses, facilitando a identificação de tendências e padrões, com um design visual elegante e responsivo.

---

## 🤝 Contato

Para dúvidas, sugestões ou colaborações, entre em contato:  

- GitHub: [brodyandre](https://github.com/brodyandre)  
- Email: (adicione seu email aqui, se desejar)  

---

> Desenvolvido com 💙 por brodyandre
